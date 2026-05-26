---
layout: default
title: Industrial & Systems Engineering
permalink: /industrial-systems/
---

<div class="pkj-projects-page">

  <p class="pkj-projects-intro">
    Decision modeling, digital strategy, and AI-assisted engineering projects from the M.S. in
    Industrial &amp; Systems Engineering at UW&ndash;Madison. Systems thinking applied across
    operations, technology adoption, and launch readiness.
  </p>

  <div class="pkj-filter-bar">
    <a class="pkj-filter-pill" href="/projects/">All Projects</a>
    <a class="pkj-filter-pill" href="/manufacturing/">Manufacturing &amp; Mechanical</a>
    <a class="pkj-filter-pill pkj-filter-pill--active" href="/industrial-systems/">Industrial &amp; Systems</a>
    <a class="pkj-filter-pill" href="/data-ml/">Data Analytics &amp; ML</a>
    <a class="pkj-filter-pill" href="/research/">B.Tech. Research</a>
  </div>

  <div class="pkj-cards-grid">

    <div class="pkj-index-card">
      <div class="pkj-card-carousel" style="position:relative">
        <img src="/images/MS Projects/LRC522/Infographics of PCE.png" alt="Launch Readiness Copilot" class="pkj-carousel-active" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover">
        <img src="/images/MS Projects/LRC522/Infographics of PCE 2.png" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
        <img src="/images/MS Projects/LRC522/Screenshot 2026-05-26 062918.png" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
      </div>
      <div class="pkj-index-card-body">
        <div class="pkj-index-card-badges">
          <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
          <span class="pkj-badge pkj-badge--academic">Academic</span>
        </div>
        <p class="pkj-index-card-title">Process Capability &amp; Launch Readiness Copilot</p>
        <p class="pkj-index-card-desc">Agentic AI workflow for process stability review and launch readiness decisions. Human judgment stays in the loop by design.</p>
        <div class="pkj-index-card-footer">
          <div class="pkj-index-card-skills">
            <span class="pkj-index-skill">Agentic AI</span>
            <span class="pkj-index-skill">SPC / Cp / Cpk</span>
            <span class="pkj-index-skill">Azure</span>
          </div>
          <a class="pkj-index-card-link" href="/projects/launch-readiness-copilot/">Read &rarr;</a>
        </div>
      </div>
    </div>

    <div class="pkj-index-card">
      <div class="pkj-card-carousel" style="position:relative">
        <img src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072131.png" alt="Buy vs Rent" class="pkj-carousel-active" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover">
        <img src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072148.png" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
        <img src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072210.png" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
      </div>
      <div class="pkj-index-card-body">
        <div class="pkj-index-card-badges">
          <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
          <span class="pkj-badge pkj-badge--academic">Academic</span>
        </div>
        <p class="pkj-index-card-title">To Buy or Rent a Home as a New Grad</p>
        <p class="pkj-index-card-desc">Utility-function decision model for housing choices. Tornado plots showed which assumptions actually mattered.</p>
        <div class="pkj-index-card-footer">
          <div class="pkj-index-card-skills">
            <span class="pkj-index-skill">Decision Analysis</span>
            <span class="pkj-index-skill">Utility Functions</span>
            <span class="pkj-index-skill">Sensitivity Analysis</span>
          </div>
          <a class="pkj-index-card-link" href="/projects/buy-vs-rent-decision/">Read &rarr;</a>
        </div>
      </div>
    </div>

    <div class="pkj-index-card">
      <div class="pkj-card-carousel" style="position:relative;background:var(--pkj-surface);display:flex;align-items:center;justify-content:center">
        <span style="font-size:11px;color:var(--pkj-subtle);position:absolute">Written report &mdash; no images</span>
      </div>
      <div class="pkj-index-card-body">
        <div class="pkj-index-card-badges">
          <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
          <span class="pkj-badge pkj-badge--academic">Academic</span>
        </div>
        <p class="pkj-index-card-title">Digital Strategy Roadmap for Pro Clean Enterprises</p>
        <p class="pkj-index-card-desc">Phased digital transformation strategy with initiative sequencing, risk/ROI framing, and executive recommendations.</p>
        <div class="pkj-index-card-footer">
          <div class="pkj-index-card-skills">
            <span class="pkj-index-skill">Tech Strategy</span>
            <span class="pkj-index-skill">Roadmapping</span>
            <span class="pkj-index-skill">Executive Writing</span>
          </div>
          <a class="pkj-index-card-link" href="/projects/digital-strategy-roadmap/">Read &rarr;</a>
        </div>
      </div>
    </div>

  </div>

</div>

<script>
document.querySelectorAll('.pkj-card-carousel').forEach(function(c){
  var imgs = c.querySelectorAll('img');
  if(imgs.length < 2) return;
  var cur = 0;
  setInterval(function(){
    imgs[cur].style.opacity='0';imgs[cur].classList.remove('pkj-carousel-active');
    cur=(cur+1)%imgs.length;
    imgs[cur].style.opacity='1';imgs[cur].classList.add('pkj-carousel-active');
  },5000);
});
</script>
