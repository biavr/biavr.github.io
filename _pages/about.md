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
  background: linear-gradient(135deg, rgba(17,24,39,0.96), rgba(30,41,59,0.88));
  color: #f8fafc;
  border-radius: 18px;
  padding: 1.5rem 1.5rem 1.2rem;
  margin: 1rem 0 1.5rem;
  box-shadow: 0 18px 40px rgba(15, 23, 42, 0.12);
}
.research-hero h3 {
  color: #f8fafc;
  margin-top: 0;
  margin-bottom: 0.6rem;
}
.research-hero p {
  color: rgba(248,250,252,0.9);
  margin-bottom: 0.8rem;
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
  margin: 1.25rem 0 1.5rem;
}
.research-card {
  background: #f8fafc;
  border: 1px solid rgba(148, 163, 184, 0.3);
  border-radius: 14px;
  padding: 1rem 1.1rem;
  box-shadow: 0 8px 20px rgba(15, 23, 42, 0.04);
}
.research-card h4 {
  margin-top: 0;
  margin-bottom: 0.35rem;
  color: #0f172a;
}
.research-card p {
  margin-bottom: 0;
  color: #334155;
}
.plan-stage {
  display: grid;
  grid-template-columns: 1.1fr 2.2fr;
  gap: 1rem;
  margin-bottom: 1rem;
  background: #ffffff;
  border: 1px solid rgba(148, 163, 184, 0.25);
  border-radius: 14px;
  padding: 1rem 1.1rem;
}
.plan-stage .label {
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  font-weight: 700;
  color: #475569;
  margin-bottom: 0.25rem;
}
.plan-stage .title {
  font-weight: 700;
  color: #0f172a;
  margin-bottom: 0.35rem;
}
.plan-stage ul {
  margin: 0.4rem 0 0 1.1rem;
  padding: 0;
}
.plan-stage li {
  margin-bottom: 0.35rem;
}
@media (max-width: 700px) {
  .plan-stage {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="research-hero">
  <h3>PhD Research Focus</h3>
  <p>
    I started my PhD in 2024 and work at the intersection of <strong>autonomous driving perception</strong>, <strong>3D occupancy understanding</strong>, and <strong>trajectory planning</strong>.
    My current direction is to build robust, real-time models that combine efficient scene representations with strong safety signals for planning in dynamic and partially unknown driving environments.
  </p>
  <div class="research-actions">
    <a class="btn btn--primary" href="/files/Bianca_Avram_PhD_Report_Research_Study.pdf" target="_blank" rel="noopener">View PhD report</a>
    <a class="btn btn--light" href="#research-plan">Read the research plan</a>
  </div>
</div>

I am a **PhD student** in computer science and an **automotive software engineer**, working on perception and planning for intelligent vehicles in highly dynamic conditions. My research focuses on how to combine compact scene representations with occupancy-based reasoning so that autonomous systems can safely navigate when the environment is uncertain, partially observed, or contains out-of-distribution obstacles.

<div class="research-grid">
  <div class="research-card">
    <h4>Starting point</h4>
    <p>Strong background in automotive software, ADAS perception, and real-world deployment constraints.</p>
  </div>
  <div class="research-card">
    <h4>Current direction</h4>
    <p>NavSim as the main benchmark and <em>DiffusionDrive</em> as the planning baseline for trajectory generation.</p>
  </div>
  <div class="research-card">
    <h4>Core objective</h4>
    <p>Integrate lightweight occupancy reasoning with planning so safety and realism improve together.</p>
  </div>
</div>

### Research interests

* **3D occupancy and scene understanding:** occupancy networks, voxelized semantics, BEV feature extraction, multi-camera fusion.
* **Autonomous driving planning:** end-to-end driving, trajectory generation, differentiable cost formulations, risk-aware decision making.
* **Real-time perception systems:** efficient architectures, deployment constraints, sensor fusion for urban and unstructured driving conditions.

---

### Research plan

<div id="research-plan">
  <div class="plan-stage">
    <div>
      <div class="label">Stage 1</div>
      <div class="title">Starting point</div>
    </div>
    <div>
      <p>Establish a strong baseline using <strong>NavSim</strong> and <strong>DiffusionDrive</strong> to study trajectory generation under realistic closed-loop driving conditions.</p>
      <ul>
        <li>Understand the benchmark, scoring logic, and planning failure modes.</li>
        <li>Reproduce the baseline and identify what is missing for safety-critical edge cases.</li>
        <li>Use the report as the first research foundation to structure the PhD direction.</li>
      </ul>
    </div>
  </div>

  <div class="plan-stage">
    <div>
      <div class="label">Stage 2</div>
      <div class="title">Lightweight occupancy integration</div>
    </div>
    <div>
      <p>Introduce a <strong>lightweight occupancy head</strong> that complements the planner and provides richer spatial uncertainty information alongside DiffusionDrive.</p>
      <ul>
        <li>Fuse occupancy reasoning with the planning stack.</li>
        <li>Capture static and dynamic obstacles in a compact representation.</li>
        <li>Keep the architecture efficient enough for near-real-time deployment.</li>
      </ul>
    </div>
  </div>

  <div class="plan-stage">
    <div>
      <div class="label">Stage 3</div>
      <div class="title">Safety-aware trajectory objectives</div>
    </div>
    <div>
      <p>Move beyond pure imitation or generation by adding occupancy-informed objectives that push the planner toward safer motion under uncertainty.</p>
      <ul>
        <li>Explore differentiable collision and risk-aware sampling strategies.</li>
        <li>Connect occupancy predictions to action quality and trajectory scoring.</li>
        <li>Emphasize robustness in rare, critical, and out-of-distribution scenarios.</li>
      </ul>
    </div>
  </div>

  <div class="plan-stage">
    <div>
      <div class="label">Stage 4</div>
      <div class="title">Objectives and end goal</div>
    </div>
    <div>
      <p>The main objective is to build a planning framework that is both <strong>realistic</strong> and <strong>safety-aware</strong>, enabling autonomous vehicles to act more confidently in cluttered and uncertain environments.</p>
      <ul>
        <li>Improve closed-loop driving quality on NavSim.</li>
        <li>Demonstrate that lightweight occupancy guidance helps DiffusionDrive.</li>
        <li>Translate this into solid PhD contributions, validation, and publications.</li>
      </ul>
    </div>
  </div>
</div>

---

### Background

* **Software Engineer** in automotive systems and perception-focused development.
* **PhD researcher** in autonomous driving, with an emphasis on 3D scene understanding, planning, and safety-aware motion generation.
* Research direction grounded in a practical understanding of onboard perception constraints and a strong interest in real-time, deployment-ready systems.
