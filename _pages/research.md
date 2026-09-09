---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-page {
  margin-top: 1rem;
}
.hero-block {
  background: linear-gradient(135deg, rgba(15, 23, 42, 0.97), rgba(30, 64, 175, 0.86));
  color: #f8fafc;
  border-radius: 18px;
  padding: 1.5rem 1.3rem;
  margin-bottom: 1.5rem;
}
.hero-block h2 {
  color: #f8fafc;
  margin-top: 0;
  margin-bottom: 0.5rem;
}
.roadmap-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin: 1.5rem 0;
}
.roadmap-card {
  background: #fff;
  border: 1px solid rgba(148, 163, 184, 0.28);
  border-radius: 14px;
  padding: 1rem 1.1rem;
  box-shadow: 0 10px 18px rgba(15, 23, 42, 0.04);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.roadmap-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 14px 24px rgba(15, 23, 42, 0.08);
}
.roadmap-card .stage {
  display: inline-block;
  font-size: 0.72rem;
  letter-spacing: 0.09em;
  text-transform: uppercase;
  color: #475569;
  font-weight: 700;
  margin-bottom: 0.45rem;
}
.roadmap-card h3 {
  margin-top: 0;
  margin-bottom: 0.5rem;
  color: #0f172a;
}
.milestone {
  margin: 1.5rem 0;
  padding: 1rem 1.2rem;
  border-left: 5px solid #16a34a;
  border-radius: 12px;
  background: linear-gradient(135deg, rgba(220, 252, 231, 0.7), rgba(239, 246, 255, 0.85));
}
.milestone h3 {
  margin-top: 0;
  color: #14532d;
}
</style>

<div class="research-page">
  <div class="hero-block">
    <h2>Research direction</h2>
    <p>
      My PhD is centered on the challenge of building <strong>safe, robust, and efficient planning systems</strong> for autonomous driving.
      I am specifically interested in the role of <strong>3D occupancy reasoning</strong> and <strong>realistic closed-loop evaluation</strong> in improving motion planning and scene understanding in dynamic driving environments.
    </p>
  </div>

  <div class="roadmap-grid">
    <div class="roadmap-card">
      <div class="stage">Phase 1</div>
      <h3>Starting point</h3>
      <p>Develop a strong baseline using <strong>NavSim</strong> and <strong>DiffusionDrive</strong>, with a focus on realistic closed-loop driving behavior.</p>
    </div>
    <div class="roadmap-card">
      <div class="stage">Phase 2</div>
      <h3>Occupancy integration</h3>
      <p>Explore how a lightweight occupancy head can enrich planning with spatial risk awareness and uncertainty information.</p>
    </div>
    <div class="roadmap-card">
      <div class="stage">Phase 3</div>
      <h3>Safety-aware objectives</h3>
      <p>Design occupancy-informed costs and robust trajectory objectives that make action selection safer in critical situations.</p>
    </div>
    <div class="roadmap-card">
      <div class="stage">Phase 4</div>
      <h3>Paper-ready contributions</h3>
      <p>Translate the strongest findings into a first PhD contribution with publication-ready validation and clear technical novelty.</p>
    </div>
  </div>

  <div class="milestone">
    <h3>Milestone goal: first paper in 2026</h3>
    <p>
      The immediate objective is to convert the current research direction into a strong publication before the end of 2026. This will serve as the first major PhD contribution and provide a firm foundation for the remaining years of the program.
    </p>
  </div>

  <h3>Core research themes</h3>
  <ul>
    <li><strong>3D occupancy perception:</strong> lightweight, efficient, and geometry-aware scene understanding.</li>
    <li><strong>Autonomous driving planning:</strong> trajectory generation, risk-aware reasoning, and decision quality under uncertainty.</li>
    <li><strong>Real-world practicality:</strong> balancing novelty with real-time feasibility and deployment-oriented constraints.</li>
    <li><strong>Evaluation and benchmarking:</strong> using NavSim and related standards to compare methods under realistic closed-loop conditions.</li>
  </ul>

  <h3>Key methodological references</h3>
  <ul>
    <li><a href="https://arxiv.org/search/?query=SparseDrive" target="_blank" rel="noopener">SparseDrive</a></li>
    <li><a href="https://arxiv.org/search/?query=DiffusionDrive" target="_blank" rel="noopener">DiffusionDrive</a></li>
    <li><a href="https://arxiv.org/search/?query=SpaRC-AD" target="_blank" rel="noopener">SpaRC-AD</a></li>
    <li><a href="https://arxiv.org/search/?query=FlashOcc" target="_blank" rel="noopener">FlashOcc</a></li>
    <li><a href="https://arxiv.org/search/?query=OPUS+autonomous+driving" target="_blank" rel="noopener">OPUS</a></li>
  </ul>

  <p>
    The long-term goal is to connect efficient scene representation, occupancy-aware safety, and planning into a coherent system that advances both the scientific understanding of autonomous driving and the practical robustness of real vehicles.
  </p>
</div>
