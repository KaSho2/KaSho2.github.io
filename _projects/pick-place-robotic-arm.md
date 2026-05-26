---
layout: default
title: "4DoF Pick & Place Robotic Arm for Assistive Care"
permalink: /projects/pick-place-robotic-arm/
description: "Designed and built a 4DoF robotic arm for elderly and disabled users. Low-cost, Arduino-driven, human-centered."
---

<div class="pkj-project-page">

  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-bt">B.Tech.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Manufacturing &amp; Mechanical</span>
    </div>
    <h1 class="pkj-project-title">4DoF Pick &amp; Place Robotic Arm for Assistive Care</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Degree</strong>B.Tech. Mini-Capstone</div>
      <div class="pkj-meta-item"><strong>Advisor</strong>Dr. C. Ramprasadh</div>
      <div class="pkj-meta-item"><strong>Team</strong>
        <a href="https://www.linkedin.com/in/satvikannadanam/" target="_blank" rel="noopener">Satvik Annadanam</a>,
        <a href="https://www.linkedin.com/in/ruchigupta09/" target="_blank" rel="noopener">Ruchi Gupta</a>
      </div>
    </div>
  </div>

  <div class="pkj-project-layout">
    <div class="pkj-project-main">

      <div class="pkj-project-summary">
        <p>Started with a straightforward question: what does someone do when their hands do not cooperate the way they used to? Designed a 4DoF pick-and-place robotic arm specifically for elderly and disabled users. The design constraints were low cost, simple operation, and a form factor that fits a home, not a lab.</p>
        <p>Modeled the full structure in SolidWorks, selected servo motors sized for the required reach and payload, and wrote the control logic in Arduino. Four degrees of freedom gave enough flexibility for useful pick-and-place tasks without overcomplicating the mechanism or the control interface.</p>
        <p>The hardest part was designing for the actual user. How does someone with limited grip strength or reduced dexterity interact with this device? That question shaped every mechanical decision, from joint angles to actuator placement to how the end effector closes. Usability was not an afterthought.</p>
      </div>

      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">SolidWorks (CAD)</span>
        <span class="pkj-project-skill-tag">Arduino</span>
        <span class="pkj-project-skill-tag">Servo Motor Selection</span>
        <span class="pkj-project-skill-tag">Motion Control</span>
        <span class="pkj-project-skill-tag">3D Printing &amp; Prototyping</span>
        <span class="pkj-project-skill-tag">Human-Centered Design</span>
        <span class="pkj-project-skill-tag">System Integration</span>
      </div>

      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery">
        <div class="pkj-gallery-grid">
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/MCP/4DoF CAD Model.png" alt="4DoF CAD Model"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/MCP/4 DoF Model.jpg" alt="4DoF Full Model"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/MCP/4DoF 3D Printed Parts.png" alt="3D Printed Parts"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/MCP/4DoF 3D Printed Parts 2.png" alt="3D Printed Parts 2"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/MCP/Kc4.jpg" alt="Assembled System"></div>
        </div>
      </div>

    </div>

    <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/PICK  AND PLACE ROBOTIC ARM FOR THE ELDERLY AND DISABLED - Report.pdf" target="_blank" rel="noopener">
          <span class="pkj-pdf-icon">&#128196;</span>
          <div><span class="pkj-pdf-label">Full Project Report</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div>
        </a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">SASTRA University</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">B.Tech. Mini-Capstone</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Category</span><span class="pkj-sidebar-row-value">Manufacturing &amp; Mechanical</span></div>
      </div>
    </div>
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
