---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
  .cv-wrap {
    max-width: 1100px;
    margin: 0 auto;
    font-size: 1rem;
    line-height: 1.6;
    color: rgba(15, 23, 42, 0.82);
  }

  .cv-header {
    background: linear-gradient(135deg, rgba(15, 23, 42, 0.98), rgba(30, 64, 175, 0.9));
    color: #ffffff;
    border-radius: 18px;
    padding: 1.6rem 1.5rem 1.3rem;
    box-shadow: 0 16px 40px rgba(15, 23, 42, 0.12);
    margin-bottom: 1.6rem;
  }

  .cv-header h1 {
    margin: 0 0 0.2rem;
    font-size: 2.2rem;
    line-height: 1.2;
    color: #ffffff;
  }

  .cv-subtitle {
    font-size: 1.08rem;
    color: rgba(255,255,255,0.88);
    margin-bottom: 0.9rem;
    font-weight: 600;
  }

  .cv-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem 1rem;
    font-size: 0.94rem;
  }

  .cv-meta a {
    color: #e2e8f0 !important;
  }

  .cv-badges {
    margin-top: 1rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }

  .cv-badge {
    display: inline-block;
    padding: 0.38rem 0.7rem;
    border-radius: 999px;
    background: rgba(255,255,255,0.12);
    border: 1px solid rgba(255,255,255,0.14);
    color: #f8fafc;
    font-size: 0.8rem;
    font-weight: 600;
  }

  .cv-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1.2rem;
  }

  .cv-panel {
    background: #ffffff;
    border: 1px solid rgba(15, 23, 42, 0.08);
    border-radius: 16px;
    padding: 1.15rem 1.2rem;
    box-shadow: 0 8px 24px rgba(15, 23, 42, 0.04);
  }

  .cv-panel h3 {
    margin: 0 0 0.8rem;
    padding-bottom: 0.35rem;
    border-bottom: 1px solid rgba(148, 163, 184, 0.25);
    font-size: 1.08rem;
    letter-spacing: 0.01em;
    color: #0f172a;
  }

  .cv-list {
    margin: 0;
    padding-left: 1.2rem;
  }

  .cv-list li {
    margin-bottom: 0.6rem;
    line-height: 1.55;
  }

  .cv-item {
    margin-bottom: 0.8rem;
  }

  .cv-item-header {
    display: flex;
    justify-content: space-between;
    gap: 0.8rem;
    flex-wrap: wrap;
    margin-bottom: 0.15rem;
  }

  .cv-item-title {
    font-weight: 700;
    color: #0f172a;
  }

  .cv-item-date {
    color: rgba(15, 23, 42, 0.7);
    font-size: 0.88rem;
    white-space: nowrap;
  }

  @media (max-width: 860px) {
    .cv-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="cv-wrap">
  <div class="cv-header">
    <h1>Bianca-Veronica Avram</h1>
    <div class="cv-subtitle">PhD Student | Autonomous Driving Research</div>
    <div class="cv-meta">
      <span>Technical University of Cluj-Napoca</span>
      <span>Cluj-Napoca, Romania</span>
      <span><a href="mailto:veronica.avram@campus.utcluj.ro">veronica.avram@campus.utcluj.ro</a></span>
      <span><a href="https://scholar.google.com/citations?hl=en&user=_lSAAeIAAAAJ" target="_blank" rel="noopener">Google Scholar</a></span>
      <span><a href="https://github.com/biavr" target="_blank" rel="noopener">GitHub</a></span>
    </div>
    <div class="cv-badges">
      <span class="cv-badge">Autonomous Driving</span>
      <span class="cv-badge">3D Occupancy</span>
      <span class="cv-badge">Planning</span>
      <span class="cv-badge">Safety-Aware AI</span>
    </div>
  </div>

  <div class="cv-grid">
    <div class="cv-panel">
      <h3>Summary</h3>
      <p>
        I am a PhD student in computer science and an automotive software engineer working at the intersection of autonomous driving perception,
        3D occupancy reasoning, and trajectory planning. My research focuses on efficient, safety-aware, and uncertainty-aware systems that can
        understand complex environments and make robust decisions in dynamic, partially observed, and real-world conditions.
      </p>
    </div>

    <div class="cv-panel">
      <h3>Research interests</h3>
      <ul class="cv-list">
        <li><strong>3D occupancy and environment understanding</strong> for autonomous vehicles.</li>
        <li><strong>Autonomous driving and motion planning</strong> under uncertainty and real-world constraints.</li>
        <li><strong>Risk-aware decision making</strong> and closed-loop evaluation.</li>
        <li><strong>Benchmarking with NavSim</strong> and related safety-oriented driving frameworks.</li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Education</h3>
      <ul class="cv-list">
        <li class="cv-item">
          <div class="cv-item-header">
            <span class="cv-item-title">PhD Student, Computer Science</span>
            <span class="cv-item-date">2024 – Present</span>
          </div>
          <div>Technical University of Cluj-Napoca</div>
          <div>Research focus: autonomous driving, 3D occupancy perception, and trajectory planning.</div>
        </li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Professional experience</h3>
      <ul class="cv-list">
        <li class="cv-item">
          <div class="cv-item-header">
            <span class="cv-item-title">PhD Researcher</span>
            <span class="cv-item-date">2024 – Present</span>
          </div>
          <div>Technical University of Cluj-Napoca</div>
          <div>Research in perception-driven autonomous driving, occupancy-based scene understanding, and risk-aware planning.</div>
        </li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Publications</h3>
      <ul class="cv-list">
        <li class="cv-item">
          <div class="cv-item-title">Freespace and Optical Flow Fusion for Generic Contours Accumulation</div>
          <div>Co-authored IEEE publication, 2025.</div>
        </li>
        <li class="cv-item">
          <div class="cv-item-title">Paper Title Number 5</div>
          <div>Conference publication, 2024.</div>
        </li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Talks and presentations</h3>
      <ul class="cv-list">
        <li class="cv-item">
          <div class="cv-item-header">
            <span class="cv-item-title">Autonomous Driving Research Seminar</span>
            <span class="cv-item-date">2024</span>
          </div>
          <div>Technical University of Cluj-Napoca</div>
          <div>Topic: scene understanding, occupancy reasoning, and planning for intelligent vehicles.</div>
        </li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Skills</h3>
      <ul class="cv-list">
        <li><strong>Core methods:</strong> 3D occupancy perception, trajectory planning, risk-aware optimization, uncertainty-aware decision making.</li>
        <li><strong>Research benchmarks:</strong> NavSim and other closed-loop evaluation frameworks.</li>
        <li><strong>Programming and engineering:</strong> Python, autonomous software design, algorithm prototyping, research-driven development.</li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Teaching and mentorship</h3>
      <ul class="cv-list">
        <li>Research-oriented technical work in autonomous systems and intelligent mobility.</li>
        <li>Academic communication and reproducible, publication-focused research workflows.</li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Service and engagement</h3>
      <ul class="cv-list">
        <li>Active participation in research, benchmarking, and engineering work related to intelligent driving systems.</li>
        <li>Contribution to reproducible experimentation and publication-focused software processes.</li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Awards and recognition</h3>
      <ul class="cv-list">
        <li>Research activity aligned with publication, benchmarking, and innovation in autonomous driving.</li>
        <li>Focused on safe, realistic, and deployable perception-planning systems for real-world environments.</li>
      </ul>
    </div>

    <div class="cv-panel">
      <h3>Languages</h3>
      <ul class="cv-list">
        <li>Romanian (native)</li>
        <li>English (professional working proficiency)</li>
      </ul>
    </div>
  </div>
</div>
