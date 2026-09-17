---
layout: archive
title: "Work in Progress"
permalink: /wip/
author_profile: true
---

{% include base_path %}

Live tracker for the current research sprint: adding a lightweight height + semantic occupancy head to VAD's stage-1 scene representation, on nuScenes. Updated as work progresses — check off items as they're done.

**Base model:** VAD (stage 1 only — perception backbone, no planning head yet)
**Data:** nuScenes + nuScenes-lidarseg
**Current phase:** _(update this line each week — e.g. "Objective 2, Week 1–2")_

---

## Objective 1 — Ground-truth construction & caching
*Week 1*

- [ ] LiDAR → BEV projection function (ego/BEV frame transform, binning)
- [ ] Decide sweep aggregation strategy (single keyframe vs. multi-sweep) and implement
- [ ] Per-cell height computation (top-of-return height)
- [ ] Join with nuScenes-lidarseg point labels; per-cell class via majority vote
- [ ] Define & implement collapsed class mapping (32 → handful: drivable / vehicle / pedestrian / obstacle / free)
- [ ] Visual sanity check: height + class map overlaid on camera image, handful of samples
- [ ] Full precompute run across training keyframes; save as compressed per-sample cache
- [ ] Verify total cache footprint (~2–3GB expected)
- [ ] Cache-loading function integrated into VAD's `__getitem__`, dataloader speed unaffected

## Objective 2 — Decoder implementation
*Week 1–2*

- [ ] Identify shared dense BEV feature tensor in VAD's forward pass (pre-sparsification)
- [ ] Height regression head (conv stack → 1-channel output)
- [ ] Semantic classification head (conv stack → C-channel output)
- [ ] Wire both heads to shared BEV feature, parallel to existing heads
- [ ] Height loss (smooth-L1) + semantic loss (cross-entropy/focal)
- [ ] Integrate both losses into VAD's multi-task loss aggregation, configurable weights
- [ ] Single batch forward+backward sanity check — gradients flow, no NaNs

## Objective 3 — Tiny PoC training & debug
*Week 2–3*

- [ ] Short training run on VAD-Tiny with new heads active
- [ ] Confirm height + semantic loss curves decreasing
- [ ] Confirm existing detection/map/motion losses stable (no spikes/plateaus)
- [ ] **Checkpoint 1 (go/no-go):** visualize predicted vs. cached GT on validation samples
- [ ] If failed: isolate data vs. model/loss issue before proceeding

## Objective 4 — Loss-weight tuning
*Week 3–4*

- [ ] Define loss-weight sweep grid
- [ ] Launch parallel Tiny runs across GPUs
- [ ] Compare impact on existing-task losses per weight
- [ ] Select working weight; confirm reproducibility with a repeat run

## Objective 5 — Regression check at Tiny scale
*Week 4*

- [ ] Train/confirm vanilla VAD-Tiny stage-1 baseline (same data/seed/schedule)
- [ ] Compute detection mAP / map metrics / motion metrics, baseline vs. +occupancy
- [ ] Confirm no meaningful regression (else: back to Objective 4)
- [ ] Record Tiny-scale numbers — first defensible ablation entry

## Objective 6 — Port to Base & full training
*Week 5*

- [ ] Verify/regenerate cached GT at VAD-Base's BEV resolution
- [ ] Port exact head architecture, losses, tuned weight from Tiny (no re-tuning)
- [ ] Launch full VAD-Base stage-1 training with occupancy heads
- [ ] Sanity-check early loss curves against Tiny's shape

## Objective 7 — Base-scale evaluation
*Week 5–6*

- [ ] Standalone occupancy quality: height RMSE/MAE, semantic mIoU per class
- [ ] Regression check repeated at Base scale
- [ ] First reportable results table: baseline vs. +occupancy
- [ ] Qualitative BEV figures (incl. a corner-case example if found)

## Objective 8 — Plan stage-2 integration
*Week 7 — planning only*

- [ ] Decide integration mechanism (pooled path features / auxiliary collision loss / query concat)
- [ ] Identify stage-2 regression checks needed (planning L2/collision, with vs. without occupancy)
- [ ] Scope as its own week-by-week plan once Objective 7 results are in

---

### Notes / decisions log
*(running log — append short dated entries as decisions get made, e.g. class mapping choices, weight values that worked, things that broke)*

-