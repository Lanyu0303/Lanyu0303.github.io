---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a second-year master's student at the [University of Science and Technology of China (USTC)](https://en.ustc.edu.cn/), advised by [Prof. Fuli Feng](https://scholar.google.com/citations?user=QePM4u8AAAAJ). Previously, I received my bachelor's degree from USTC in 2024. I expect to graduate in <strong style="color:#1a73e8;">2027.06</strong>.

My research interest mainly lies in:

- **LLM-based agents and agentic RL**
- **LLMs for Recommendation**

I am currently seeking full-time industry opportunities. Please feel free to reach out to me via [email](mailto:caishihao@mail.ustc.edu.cn).

## Experience

<style>
.exp-timeline {
  position: relative;
  padding-left: 24px;
  margin-top: 16px;
}
.exp-timeline::before {
  content: '';
  position: absolute;
  left: 5px;
  top: 8px;
  bottom: 8px;
  width: 2px;
  background: linear-gradient(180deg, #1a73e8 0%, #34a853 100%);
  border-radius: 1px;
}
.exp-item {
  position: relative;
  margin-bottom: 22px;
  padding-left: 20px;
}
.exp-item::before {
  content: '';
  position: absolute;
  left: -20px;
  top: 6px;
  width: 10px;
  height: 10px;
  background: #fff;
  border: 2.5px solid #1a73e8;
  border-radius: 50%;
  z-index: 1;
}
.exp-item:last-child::before {
  border-color: #34a853;
}
.exp-date {
  font-size: 0.82em;
  color: #5f6368;
  font-weight: 500;
  letter-spacing: 0.3px;
}
.exp-header {
  display: flex;
  align-items: baseline;
  gap: 8px;
  margin-top: 2px;
}
.exp-org {
  font-size: 1.05em;
  font-weight: 600;
  color: #202124;
}
.exp-team {
  font-size: 1.05em;
  color: #1a73e8;
  font-weight: 500;
}
.exp-desc {
  font-size: 0.88em;
  color: #444;
  margin-top: 4px;
  line-height: 1.5;
}
</style>

<div class="exp-timeline">
  <div class="exp-item">
    <div class="exp-date">2026.03 — Present</div>
    <div class="exp-header">
      <span class="exp-org">Alibaba · Tongyi Lab</span>
      <span class="exp-team">Qwen Team</span>
    </div>
    <div class="exp-desc">Focusing on agent-related data for LLM pre-training.</div>
  </div>
  <div class="exp-item">
    <div class="exp-date">2025.12 — 2026.03</div>
    <div class="exp-header">
      <span class="exp-org">Moonshot AI (Kimi)</span>
      <span class="exp-team">RL Team</span>
    </div>
    <div class="exp-desc">Agentic post-training for tool use and skill following.</div>
  </div>
  <div class="exp-item">
    <div class="exp-date">2025.08 — 2025.12</div>
    <div class="exp-header">
      <span class="exp-org">Alibaba · Tongyi Lab</span>
      <span class="exp-team">DeepResearch Team</span>
    </div>
    <div class="exp-desc">Agentic post-training for tool use and environment scaling.</div>
  </div>
</div>

## Technical Reports

<style>
.tr-list {
  margin-top: 14px;
}
.tr-card {
  display: flex;
  align-items: flex-start;
  gap: 10px;
  padding: 10px 14px;
  margin-bottom: 10px;
  background: #f8f9fa;
  border-radius: 8px;
  border-left: 3px solid #1a73e8;
  transition: background 0.2s, transform 0.15s;
  text-decoration: none;
  color: inherit;
}
.tr-card:hover {
  background: #eef3ff;
  transform: translateX(3px);
}
.tr-icon {
  flex-shrink: 0;
  width: 18px;
  height: 18px;
  margin-top: 2px;
  color: #1a73e8;
}
.tr-title {
  font-size: 0.98em;
  font-weight: 500;
  color: #202124;
}
.tr-badge {
  display: inline-block;
  font-size: 0.7em;
  color: #fff;
  background: #1a73e8;
  padding: 1px 6px;
  border-radius: 4px;
  margin-left: 6px;
  vertical-align: middle;
}
</style>

<div class="tr-list">
  <a href="https://arxiv.org/pdf/2602.02276" target="_blank" class="tr-card">
    <svg class="tr-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
      <polyline points="14 2 14 8 20 8"></polyline>
    </svg>
    <div>
      <span class="tr-title">Kimi K2.5 Technical Report</span>
      <span class="tr-badge">arXiv</span>
    </div>
  </a>
  <a href="https://arxiv.org/pdf/2510.24701" target="_blank" class="tr-card">
    <svg class="tr-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
      <polyline points="14 2 14 8 20 8"></polyline>
    </svg>
    <div>
      <span class="tr-title">Tongyi DeepResearch Technical Report</span>
      <span class="tr-badge">arXiv</span>
    </div>
  </a>
</div>

## First-Author & Co-First-Author Papers

<style>
.pub-list {
  margin-top: 14px;
}
.pub-card {
  display: block;
  padding: 10px 14px;
  margin-bottom: 10px;
  background: #f8f9fa;
  border-radius: 8px;
  border-left: 3px solid #34a853;
  transition: background 0.2s, transform 0.15s;
  text-decoration: none;
  color: inherit;
}
.pub-card:hover {
  background: #eef7f0;
  transform: translateX(3px);
}
.pub-title {
  font-size: 0.98em;
  font-weight: 500;
  color: #202124;
  line-height: 1.4;
}
.pub-venue {
  font-size: 0.78em;
  color: #5f6368;
  margin-top: 3px;
}
.pub-venue strong {
  color: #34a853;
}
</style>

<div class="pub-list">
  <a href="https://arxiv.org/pdf/2512.22857" target="_blank" class="pub-card">
    <div class="pub-title">AutoForge: Automated Environment Synthesis for Agentic Reinforcement Learning</div>
    <div class="pub-venue"><strong>arXiv</strong></div>
  </a>
  <a href="https://arxiv.org/pdf/2509.13311v1" target="_blank" class="pub-card">
    <div class="pub-title">Towards General Agentic Intelligence via Environment Scaling</div>
    <div class="pub-venue"><strong>arXiv</strong></div>
  </a>
  <a href="https://arxiv.org/pdf/2506.00441" target="_blank" class="pub-card">
    <div class="pub-title">K-order Ranking Preference Optimization for Large Language Models</div>
    <div class="pub-venue"><strong>ACL 2025 Findings</strong></div>
  </a>
  <a href="https://arxiv.org/pdf/2510.22888" target="_blank" class="pub-card">
    <div class="pub-title">MGFRec: Towards Reinforced Reasoning Recommendation with Multiple Groundings and Feedback</div>
    <div class="pub-venue"><strong>KDD 2026</strong></div>
  </a>
  <a href="https://arxiv.org/pdf/2410.20027v2" target="_blank" class="pub-card">
    <div class="pub-title">Agentic Feedback Loop Modeling Improves Recommendation and User Simulation</div>
    <div class="pub-venue"><strong>SIGIR 2025</strong></div>
  </a>
  <a href="https://arxiv.org/pdf/2406.11503" target="_blank" class="pub-card">
    <div class="pub-title">GeoGPT4V: Towards Geometric Multi-modal Large Language Models with Geometric Image Generation</div>
    <div class="pub-venue"><strong>EMNLP 2024</strong></div>
  </a>
</div>
