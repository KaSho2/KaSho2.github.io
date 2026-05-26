---
layout: default
title: Lab Experience
permalink: /research/
---

<div class="pkj-research-page">

  <p class="pkj-projects-intro">
    Before the MS, before the systems engineering coursework, there was a lab.
    Two years at SASTRA working as a student lab assistant under Dr. M. Venkatesan
    in the Thermodynamics &amp; Heat Transfer Laboratory. I was not a researcher.
    I was learning what research actually looks like from the inside.
  </p>

  <div class="pkj-section-head">
    <span class="pkj-section-num">01 /</span>
    <span class="pkj-section-title">What the lab was working on</span>
    <span class="pkj-section-line"></span>
  </div>

  <div class="pkj-callout" style="margin-bottom:2rem">
    <div class="pkj-callout-label">Honest framing</div>
    <p class="pkj-callout-text" style="font-style:normal">
      The papers below were authored and led by Dr. Venkatesan's PhD students and research team.
      My role was as a lab assistant: experimental setup, COMSOL simulation runs, data collection,
      and generally trying to keep up with what was happening. I am not a co-author on either paper.
      I'm listing them here because they're the research context I learned in, and they shaped
      how I think about simulation, measurement, and the gap between the two.
    </p>
  </div>

  <!-- Paper 1: H2O2 -->
  <div class="pkj-pub-card">
    <div class="pkj-pub-journal">Materials Today: Proceedings &nbsp;&middot;&nbsp; Elsevier, 2023</div>
    <div class="pkj-pub-title">Hydrogen Peroxide Decomposition in Serpentine Mini Channel with Silver Catalyst</div>
    <div class="pkj-pub-authors">R. Sushmitha, M. Venkatesan &mdash; School of Mechanical Engineering, SASTRA Deemed University</div>
    <p class="pkj-pub-desc">
      Monopropellant thrusters using hydrogen peroxide are used in satellite micro-propulsion for
      precise attitude and orbital control. This study used COMSOL Multiphysics to compare serpentine
      vs straight mini-channels with silver catalyst at varied positions and lengths. The serpentine
      channel consistently outperformed the straight channel due to improved mixing at the bend sections.
      A 45 cm serpentine configuration achieved 99.5% decomposition of 30% H<sub>2</sub>O<sub>2</sub>.
      My lab work during this period involved COMSOL simulation runs and experimental setup assistance
      &mdash; hands-on exposure to computational fluid dynamics before I knew what to call it.
    </p>
    <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:14px">
      <span class="pkj-pub-role">Lab Assistant</span>
      <span class="pkj-pub-role">COMSOL Multiphysics</span>
      <span class="pkj-pub-role">Fluid Dynamics</span>
    </div>
    <div class="pkj-gallery-grid" style="grid-template-columns:repeat(2,1fr);max-width:400px">
      <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Research/hydrogenperoxide/Serpentine Mini Channel.png" alt="Serpentine Mini Channel"></div>
      <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Research/hydrogenperoxide/straight channel.png" alt="Straight Channel Comparison"></div>
    </div>
  </div>

  <!-- Paper 2: IR Two-Phase Flow -->
  <div class="pkj-pub-card">
    <div class="pkj-pub-journal">Recent Advances in Fluid Dynamics &nbsp;&middot;&nbsp; Springer Nature, 2023</div>
    <div class="pkj-pub-title">Shape and Size Effects of Glass Mini-Channels on Infrared Sensors in Air&ndash;Water Two-Phase Flow</div>
    <div class="pkj-pub-authors">N. Mithran, K. Sowndarya, M. Venkatesan &mdash; SASTRA Deemed University</div>
    <p class="pkj-pub-desc">
      Two-phase flow measurement in mini-channels matters for nuclear reactor water transport and
      microfluidic applications. This study examined how cross-sectional shape and diameter of borosilicate
      glass channels affect IR sensor signal output, using high-speed photography alongside COMSOL optical
      simulations. The lab work I assisted with during this project introduced me to the challenge of
      interpreting noisy sensor data and the friction between simulation results and real experimental
      conditions. That gap between model and measurement is something I kept running into in later work.
    </p>
    <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:14px">
      <span class="pkj-pub-role">Lab Assistant</span>
      <span class="pkj-pub-role">COMSOL Multiphysics</span>
      <span class="pkj-pub-role">Two-Phase Flow</span>
    </div>
    <div class="pkj-gallery-grid" style="grid-template-columns:repeat(1,1fr);max-width:200px">
      <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Research/IRTwophaseflow/524979_1_En_27_Fig1_HTML.webp" alt="IR Two-Phase Flow Setup"></div>
    </div>
  </div>

  <div class="pkj-section-head" style="margin-top:2rem">
    <span class="pkj-section-num">02 /</span>
    <span class="pkj-section-title">What I took from it</span>
    <span class="pkj-section-line"></span>
  </div>

  <p class="pkj-body-text">
    Two years in that lab before my undergraduate thesis gave me something no coursework had: a sense of
    how long research actually takes and how many iterations sit between a hypothesis and a result.
    The COMSOL work taught me simulation-driven thinking. The experimental side taught me to be
    skeptical of clean outputs. Both of those instincts have shown up in every project since.
  </p>

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
