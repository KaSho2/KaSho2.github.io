---
layout: default
title: Manufacturing & Mechanical
permalink: /manufacturing/
---

<div class="pkj-projects-page">

  <p class="pkj-projects-intro">
    Mechanical design, lean manufacturing, and additive manufacturing projects spanning
    both undergraduate and graduate work. From workstation ergonomics to topology-optimized gears
    to assistive robotics.
  </p>

  <div class="pkj-filter-bar">
    <a class="pkj-filter-pill" href="/projects/">All Projects</a>
    <a class="pkj-filter-pill pkj-filter-pill--active" href="/manufacturing/">Manufacturing &amp; Mechanical</a>
    <a class="pkj-filter-pill" href="/industrial-systems/">Industrial &amp; Systems</a>
    <a class="pkj-filter-pill" href="/data-ml/">Data Analytics &amp; ML</a>
    <a class="pkj-filter-pill" href="/research/">B.Tech. Research</a>
  </div>

  <div class="pkj-cards-grid">

    <div class="pkj-index-card">
      <div class="pkj-card-carousel" style="position:relative">
        <img src="/images/MS Projects/DB515/Screenshot 2026-05-26 063523.png" alt="Doosan Bobcat" class="pkj-carousel-active" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover">
        <img src="/images/MS Projects/DB515/Screenshot 2026-05-26 063601.png" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
        <img src="/images/MS Projects/DB515/Screenshot 2026-05-26 063637.png" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
      </div>
      <div class="pkj-index-card-body">
        <div class="pkj-index-card-badges">
          <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
          <span class="pkj-badge pkj-badge--company">Company</span>
        </div>
        <p class="pkj-index-card-title">Doosan Bobcat ZT2 Workstation 13 Process Improvement</p>
        <p class="pkj-index-card-desc">Lean improvement for a tire installation workstation. Spaghetti diagrams, MOST analysis, 5S, and a cost-benefit case that actually holds up.</p>
        <div class="pkj-index-card-footer">
          <div class="pkj-index-card-skills">
            <span class="pkj-index-skill">Lean / 5S</span>
            <span class="pkj-index-skill">MOST</span>
            <span class="pkj-index-skill">Ergonomics</span>
          </div>
          <a class="pkj-index-card-link" href="/projects/doosan-bobcat-process-improvement/">Read &rarr;</a>
        </div>
      </div>
    </div>

    <div class="pkj-index-card">
      <div class="pkj-card-carousel" style="position:relative">
        <img src="/images/BTech Projects/GAMTO/Generative Design Spur Gear.jpg" alt="Gear AM Topology" class="pkj-carousel-active" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover">
        <img src="/images/BTech Projects/GAMTO/Topology Optimized Design.jpg" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
        <img src="/images/BTech Projects/GAMTO/OG Design Isometric.jpg" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
      </div>
      <div class="pkj-index-card-body">
        <div class="pkj-index-card-badges">
          <span class="pkj-badge pkj-badge--level-bt">B.Tech.</span>
          <span class="pkj-badge pkj-badge--academic">Academic</span>
        </div>
        <p class="pkj-index-card-title">Sustainable Gear Design via Topology Optimization &amp; Generative Design</p>
        <p class="pkj-index-card-desc">How much material can you remove from a spur gear before it fails? Ran TO and generative design in parallel, compared outputs, built the AM cost case.</p>
        <div class="pkj-index-card-footer">
          <div class="pkj-index-card-skills">
            <span class="pkj-index-skill">ANSYS</span>
            <span class="pkj-index-skill">Fusion 360</span>
            <span class="pkj-index-skill">DfAM</span>
          </div>
          <a class="pkj-index-card-link" href="/projects/gear-am-topology/">Read &rarr;</a>
        </div>
      </div>
    </div>

    <div class="pkj-index-card">
      <div class="pkj-card-carousel" style="position:relative">
        <img src="/images/BTech Projects/MCP/4DoF CAD Model.png" alt="Robotic Arm" class="pkj-carousel-active" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover">
        <img src="/images/BTech Projects/MCP/4 DoF Model.jpg" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
        <img src="/images/BTech Projects/MCP/4DoF 3D Printed Parts.png" alt="" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;transition:opacity 0.8s">
      </div>
      <div class="pkj-index-card-body">
        <div class="pkj-index-card-badges">
          <span class="pkj-badge pkj-badge--level-bt">B.Tech.</span>
          <span class="pkj-badge pkj-badge--academic">Academic</span>
        </div>
        <p class="pkj-index-card-title">4DoF Pick &amp; Place Robotic Arm for Assistive Care</p>
        <p class="pkj-index-card-desc">Designed for elderly and disabled users. Low-cost, Arduino-controlled, human-centered mechanical design.</p>
        <div class="pkj-index-card-footer">
          <div class="pkj-index-card-skills">
            <span class="pkj-index-skill">SolidWorks</span>
            <span class="pkj-index-skill">Arduino</span>
            <span class="pkj-index-skill">3D Printing</span>
          </div>
          <a class="pkj-index-card-link" href="/projects/pick-place-robotic-arm/">Read &rarr;</a>
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
