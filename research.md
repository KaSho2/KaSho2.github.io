---
layout: default
title: Research
permalink: /research/
---

<div class="pkj-research-page">

  <p class="pkj-projects-intro">
    During my undergraduate years at SASTRA University, I worked as a student researcher in
    Dr. M. Venkatesan's Thermodynamics &amp; Heat Transfer Laboratory. Both projects below
    led to peer-reviewed publications. The work was around fluid dynamics and thermal systems
    at the micro/mini-channel scale, which is where my interest in engineering research and
    simulation-driven analysis took root.
  </p>

  <div class="pkj-section-head">
    <span class="pkj-section-num">01 /</span>
    <span class="pkj-section-title">Published research</span>
    <span class="pkj-section-line"></span>
  </div>

  <!-- Paper 1: H2O2 -->
  <div class="pkj-pub-card">
    <div class="pkj-pub-journal">Materials Today: Proceedings &nbsp;&middot;&nbsp; Elsevier, 2023</div>
    <div class="pkj-pub-title">Hydrogen Peroxide Decomposition in Serpentine Mini Channel with Silver Catalyst</div>
    <div class="pkj-pub-authors">R. Sushmitha, M. Venkatesan &mdash; School of Mechanical Engineering, SASTRA Deemed University</div>
    <p class="pkj-pub-desc">
      Monopropellant thrusters using hydrogen peroxide are used in satellite micro-propulsion for precise attitude and orbital control.
      Complete catalytic decomposition of H<sub>2</sub>O<sub>2</sub> remains a hard problem. This study used COMSOL Multiphysics to
      compare serpentine vs straight mini-channels (0.25 cm diameter, 56.5 cm length) with silver catalyst placed at varied positions
      and lengths. The serpentine channel consistently outperformed the straight channel across all catalyst lengths due to improved
      mixing at the bend sections. A 45 cm serpentine configuration achieved 99.5% decomposition of 30% H<sub>2</sub>O<sub>2</sub>.
      My involvement was in the simulation work and experimental setup validation during my time in the lab.
    </p>
    <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:14px">
      <span class="pkj-pub-role">Student Researcher</span>
      <span class="pkj-pub-role">COMSOL Multiphysics</span>
      <span class="pkj-pub-role">Fluid Dynamics</span>
      <span class="pkj-pub-role">Catalytic Decomposition</span>
    </div>
    <div class="pkj-gallery-grid" style="grid-template-columns:repeat(2,1fr);max-width:400px">
      <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Research/hydrogenperoxide/Serpentine Mini Channel.png" alt="Serpentine Mini Channel"></div>
      <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Research/hydrogenperoxide/straight channel.png" alt="Straight Channel"></div>
    </div>
  </div>

  <!-- Paper 2: IR Two-Phase Flow -->
  <div class="pkj-pub-card">
    <div class="pkj-pub-journal">Recent Advances in Fluid Dynamics (Springer Nature, 2023) &nbsp;&middot;&nbsp; Lecture Notes in Mechanical Engineering</div>
    <div class="pkj-pub-title">Shape and Size Effects of Glass Mini-Channels on Infrared Sensors in Air&ndash;Water Two-Phase Flow</div>
    <div class="pkj-pub-authors">N. Mithran, K. Sowndarya, M. Venkatesan &mdash; SASTRA Deemed University</div>
    <p class="pkj-pub-desc">
      Two-phase flow regimes (bubble, slug) inside mini-channels need accurate measurement for applications in nuclear
      reactor water transport and microfluidic systems. This study examined how the cross-sectional shape (circular vs square vs
      triangular) and diameter of borosilicate glass test sections affect IR sensor signal output. Experiments were conducted using
      high-speed photography (340 fps) alongside COMSOL optical simulations. Key finding: circular tube diameter and wall thickness
      directly govern IR ray convergence and the measurable void fraction amplitude. The square channel behaved differently due to
      flat surface refraction, complicating direct comparison with circular sections. My role was in the COMSOL simulation setup
      and experimental data collection in the lab.
    </p>
    <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:14px">
      <span class="pkj-pub-role">Student Researcher</span>
      <span class="pkj-pub-role">COMSOL Multiphysics</span>
      <span class="pkj-pub-role">IR Sensing</span>
      <span class="pkj-pub-role">Two-Phase Flow</span>
      <span class="pkj-pub-role">High-Speed Imaging</span>
    </div>
    <div class="pkj-gallery-grid" style="grid-template-columns:repeat(1,1fr);max-width:200px">
      <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Research/IRTwophaseflow/524979_1_En_27_Fig1_HTML.webp" alt="IR Two-Phase Flow Setup"></div>
    </div>
  </div>

  <div class="pkj-callout" style="margin-top:2rem">
    <div class="pkj-callout-label">A note on my role</div>
    <p class="pkj-callout-text" style="font-style:normal">
      Both publications came out of Dr. Venkatesan's lab, where I worked as a student researcher and assistant to PhD candidates.
      My contributions were in COMSOL simulation setup, experimental data collection, and analysis. The listed authors are the primary
      researchers who led the work.
    </p>
  </div>

</div>

<script>
document.querySelectorAll('.pkj-gallery-img').forEach(function(img){
  img.addEventListener('click',function(){
    var o=document.createElement('div');o.className='pkj-lightbox';
    o.innerHTML='<div class="pkj-lightbox-inner"><img src="'+img.src+'"><div class="pkj-lightbox-close">&times;</div></div>';
    document.body.appendChild(o);
    o.querySelector('.pkj-lightbox-close').addEventListener('click',function(){o.remove();});
    o.addEventListener('click',function(e){if(e.target===o)o.remove();});
  });
});
</script>
