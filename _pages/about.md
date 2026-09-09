---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.research-hero {
  background: linear-gradient(135deg, rgba(15, 23, 42, 0.98), rgba(30, 64, 175, 0.85));
  color: #f8fafc;
  border-radius: 18px;
  padding: 1.7rem 1.5rem 1.3rem;
  margin: 0.5rem 0 1.5rem;
  box-shadow: 0 20px 45px rgba(15, 23, 42, 0.15);
}
.research-hero h3 {
  color: #f8fafc;
  margin-top: 0;
  margin-bottom: 0.75rem;
}
.research-hero p {
  color: rgba(248,250,252,0.92);
  margin-bottom: 0.9rem;
}
.research-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
  margin-top: 1rem;
}
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin: 1.5rem 0;
}
.research-card {
  background: linear-gradient(180deg, #ffffff, #f8fafc);
  border: 1px solid rgba(148, 163, 184, 0.35);
  border-radius: 14px;
  padding: 1rem 1.1rem;
  box-shadow: 0 10px 25px rgba(15, 23, 42, 0.05);
}
.research-card h4 {
  margin-top: 0;
  margin-bottom: 0.4rem;
  color: #0f172a;
}
.research-card p {
  margin-bottom: 0;
  color: #334155;
}
.hero-stats {
  display: grid;
  grid-template-columns: repeat(3, minmax(140px, 1fr));
  gap: 0.8rem;
  margin-top: 1rem;
}
.hero-stat {
  background: rgba(255,255,255,0.08);
  border: 1px solid rgba(255,255,255,0.15);
  border-radius: 12px;
  padding: 0.8rem 0.9rem;
}
.hero-stat strong {
  display: block;
  font-size: 1.1rem;
  color: #ffffff;
}
.hero-stat span {
  color: rgba(255,255,255,0.8);
  font-size: 0.85rem;
}
.paper-links {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
  gap: 0.8rem;
  margin: 1rem 0 1.5rem;
}
.paper-card {
  background: linear-gradient(180deg, #ffffff, #f8fafc);
  border: 1px solid rgba(148, 163, 184, 0.32);
  border-radius: 14px;
  padding: 1rem 1rem 0.9rem;
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.04);
}
.paper-card small {
  display: block;
  font-size: 0.72rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: #64748b;
  margin-bottom: 0.4rem;
}
.paper-card strong {
  display: block;
  color: #0f172a;
  margin-bottom: 0.3rem;
}
.paper-card p {
  margin: 0 0 0.7rem 0;
  font-size: 0.92rem;
  color: #475569;
}
.paper-card a {
  color: #1d4ed8;
  font-weight: 600;
  text-decoration: none;
}
.paper-card a:hover {
  text-decoration: underline;
}
.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin: 1.5rem 0;
}
.feature-card {
  background: linear-gradient(180deg, #ffffff, #f8fafc);
  border: 1px solid rgba(148, 163, 184, 0.3);
  border-radius: 14px;
  padding: 1rem 1.1rem;
}
.feature-card h4 {
  margin-top: 0;
  margin-bottom: 0.45rem;
  color: #0f172a;
}
.feature-card p {
  margin-bottom: 0;
  color: #475569;
}
.roadmap {
  display: grid;
  gap: 1rem;
  margin: 1.25rem 0 1.5rem;
}
.plan-stage {
  display: grid;
  grid-template-columns: 1fr 2.4fr;
  gap: 1rem;
  background: #ffffff;
  border: 1px solid rgba(148, 163, 184, 0.25);
  border-radius: 14px;
  padding: 1rem 1.1rem;
}
.plan-stage .label {
  font-size: 0.78rem;
  letter-spacing: 0.09em;
  text-transform: uppercase;
  font-weight: 700;
  color: #475569;
  margin-bottom: 0.25rem;
}
.plan-stage .title {
  font-weight: 700;
  color: #0f172a;
  margin-bottom: 0.3rem;
}
.plan-stage ul {
  margin: 0.45rem 0 0 1.1rem;
  padding: 0;
}
.plan-stage li {
  margin-bottom: 0.35rem;
}
.milestone-box {
  background: linear-gradient(135deg, rgba(220, 252, 231, 0.75), rgba(239, 246, 255, 0.9));
  border: 1px solid rgba(34, 197, 94, 0.25);
  border-left: 5px solid #16a34a;
  border-radius: 12px;
  padding: 1rem 1.1rem;
  margin-top: 1rem;
}
.milestone-box h4 {
  margin-top: 0;
  margin-bottom: 0.4rem;
  color: #14532d;
}
@media (max-width: 700px) {
  .plan-stage {
    grid-template-columns: 1fr;
  }
  .hero-stats {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="research-hero">
  <h3>PhD Research in Safe Autonomous Driving</h3>
  <p>
    I started my PhD in 2024 and work at the intersection of <strong>autonomous driving perception</strong>, <strong>3D occupancy reasoning</strong>, and <strong>trajectory planning</strong>.
    My current trajectory is to build efficient, safety-aware planning systems that combine compact scene understanding with realistic closed-loop decision making in dynamic driving environments.
  </p>
  <div class="research-actions">
    <a class="btn btn--primary" href="/files/Bianca_Avram_PhD_Report_Research_Study.pdf" target="_blank" rel="noopener">View PhD report</a>
    <a class="btn btn--light" href="/research/">Research roadmap</a>
    <a class="btn btn--inverse" href="/selected-papers/">Selected papers</a>
  </div>
  <div class="hero-stats">
    <div class="hero-stat">
      <strong>2024</strong>
      <span>PhD start</span>
    </div>
    <div class="hero-stat">
      <strong>NavSim</strong>
      <span>Core benchmark</span>
    </div>
    <div class="hero-stat">
      <strong>2026</strong>
      <span>Paper goal</span>
    </div>
  </div>
</div>

I am a **PhD student** in computer science and an **automotive software engineer**, with a focus on perception and planning for intelligent vehicles in highly dynamic scenarios. My work centers on narrowing the gap between efficient scene representations and occupancy-informed decision-making so that autonomous systems can remain both performant and safe in uncertain, partially observed, and out-of-distribution settings.

<div class="feature-grid">
  <div class="feature-card">
    <h4>Occupancy reasoning</h4>
    <p>Investigating how compact 3D occupancy signals can improve spatial understanding for modern driving stacks.</p>
  </div>
  <div class="feature-card">
    <h4>Planning safety</h4>
    <p>Designing risk-aware and uncertainty-aware objectives that move beyond purely imitation-based trajectory generation.</p>
  </div>
  <div class="feature-card">
    <h4>Benchmarking</h4>
    <p>Using <strong>NavSim</strong> as the experimental anchor to evaluate closed-loop realism and planning robustness.</p>
  </div>
  <div class="feature-card">
    <h4>Deployment realism</h4>
    <p>Balancing algorithmic novelty with real-time and sensor-driven constraints relevant to production autonomous systems.</p>
  </div>
</div>

### Research interests

* **3D occupancy and environment understanding:** occupancy networks, voxelized semantics, BEV feature extraction, multi-camera fusion.
* **Motion planning and decision making:** end-to-end driving, trajectory generation, risk-aware objectives, differentiable safety costs.
* **Real-time systems:** efficient architectures, sensor-fusion strategies, and deployment constraints for autonomous driving.

---

### Key papers and references

<div id="key-papers" class="paper-links">
  <div class="paper-card">
    <small>Planning</small>
    <strong>SparseDrive</strong>
    <p>Efficient sparse scene reasoning for autonomous driving.</p>
    <a href="https://arxiv.org/search/?query=SparseDrive" target="_blank" rel="noopener">Open paper</a>
  </div>
  <div class="paper-card">
    <small>Generative planning</small>
    <strong>DiffusionDrive</strong>
    <p>Trajectory generation through diffusion-based motion modeling.</p>
    <a href="https://arxiv.org/search/?query=DiffusionDrive" target="_blank" rel="noopener">Open paper</a>
  </div>
  <div class="paper-card">
    <small>Spatial reasoning</small>
    <strong>SpaRC-AD</strong>
    <p>Scene and motion reasoning strategies for robust driving behavior.</p>
    <a href="https://arxiv.org/search/?query=SpaRC-AD" target="_blank" rel="noopener">Open paper</a>
  </div>
  <div class="paper-card">
    <small>Occupancy</small>
    <strong>FlashOcc</strong>
    <p>Fast volumetric occupancy modeling for perception-centric autonomy.</p>
    <a href="https://arxiv.org/search/?query=FlashOcc" target="_blank" rel="noopener">Open paper</a>
  </div>
  <div class="paper-card">
    <small>Perception</small>
    <strong>OPUS</strong>
    <p>Occupancy- and uncertainty-aware methods for driving perception.</p>
    <a href="https://arxiv.org/search/?query=OPUS+autonomous+driving" target="_blank" rel="noopener">Open paper</a>
  </div>
</div>

These references are shaping the direction of my work: efficient planning, occupancy-aware representations, and realistic scene understanding under uncertainty. The goal is to integrate their strengths into a safety-oriented planning framework that fits the realities of autonomous driving.

---

### Research roadmap

<div id="research-plan" class="roadmap">
  <div class="plan-stage">
    <div>
      <div class="label">2024</div>
      <div class="title">Foundation</div>
    </div>
    <div>
      <p>Establish the thesis direction and build the technical baseline from literature, perception-planning methods, and benchmark understanding.</p>
      <ul>
        <li>Review state-of-the-art in autonomous driving perception and planning.</li>
        <li>Study <strong>NavSim</strong>, <strong>DiffusionDrive</strong>, and occupancy-based methods.</li>
        <li>Formalize the research question and define the experimental setup.</li>
      </ul>
    </div>
  </div>

  <div class="plan-stage">
    <div>
      <div class="label">2025</div>
      <div class="title">Benchmarking and baseline</div>
    </div>
    <div>
      <p>Reproduce and analyze the strongest planning baselines, then identify where occupancy guidance can improve realism and robustness.</p>
      <ul>
        <li>Benchmark <strong>DiffusionDrive</strong> and related competitors on NavSim.</li>
        <li>Characterize failure modes, unsafe trajectories, and scene-understanding limitations.</li>
        <li>Build the first structured prototype for occupancy-aware planning.</li>
      </ul>
    </div>
  </div>

  <div class="plan-stage">
    <div>
      <div class="label">2026</div>
      <div class="title">Lightweight occupancy integration</div>
    </div>
    <div>
      <p>Introduce a lightweight occupancy head or occupancy-informed objective to improve planner safety while keeping the architecture efficient and deployment-oriented.</p>
      <ul>
        <li>Fuse occupancy cues with the planning pipeline.</li>
        <li>Explore differentiable collision and risk-aware constraints.</li>
        <li>Validate the approach on realistic, closed-loop autonomous driving scenarios.</li>
      </ul>
    </div>
  </div>

  <div class="plan-stage">
    <div>
      <div class="label">2026+</div>
      <div class="title">Target milestone</div>
    </div>
    <div>
      <p>The immediate goal is to produce a strong first paper before the end of 2026, centered on occupancy-aware planning with DiffusionDrive-inspired trajectory generation.</p>
      <ul>
        <li>Demonstrate meaningful gains over the planning baseline.</li>
        <li>Publish a focused contribution on safety-aware, occupancy-informed autonomous driving.</li>
        <li>Use the paper outcome to anchor the remaining PhD trajectory and next-generation experiments.</li>
      </ul>
    </div>
  </div>
</div>

<div class="milestone-box">
  <h4>Milestone target: first paper accepted in 2026</h4>
  <p>The short-term objective is to convert the current research direction into a high-quality paper submission and aim for acceptance before the end of this year. This will serve as the first major research contribution and a strong foundation for the next stage of the PhD.</p>
</div>

---

### Academic background

* **Software Engineer** with experience in automotive and perception-oriented systems.
* **PhD researcher** focused on end-to-end autonomous driving, 3D occupancy understanding, and trajectory planning.
* Research driven by the practical need to make autonomous systems safer, more robust, and more interpretable in complex real-world settings.
