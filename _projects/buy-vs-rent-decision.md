---
layout: default
title: "To Buy or Rent a Home as a New Grad"
permalink: /projects/buy-vs-rent-decision/
description: "Decision modeling framework for housing choices, built with utility functions and sensitivity analysis."
---

<div class="pkj-project-page">

  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Industrial &amp; Systems</span>
    </div>
    <h1 class="pkj-project-title">To Buy or Rent a Home as a New Grad</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Course</strong>ISyE 516</div>
      <div class="pkj-meta-item"><strong>Advisor</strong>Dr. Tony McDonald</div>
      <div class="pkj-meta-item"><strong>Team</strong>
        Jose Perales Sorni,
        <a href="https://www.linkedin.com/in/kaushik-kannan-ramakrishnan/" target="_blank" rel="noopener">Kaushik Ramakrishnan</a>,
        <a href="https://www.linkedin.com/in/sinfeneyt/" target="_blank" rel="noopener">Sinfeney Teng</a>
      </div>
    </div>
  </div>

  <div class="pkj-project-layout">
    <div class="pkj-project-main">

      <div class="pkj-project-summary">
        <p>Housing decisions for new grads are rarely straightforward. Market conditions, income uncertainty, lifestyle flexibility, and long-term wealth goals all pull in different directions. This project built a decision framework that takes those competing factors seriously rather than defaulting to a single metric.</p>
        <p>Used a utility-function-based approach to model preferences across different scenarios. External inputs included housing market trends and demographic data to ground the assumptions in real numbers. Sensitivity analysis (tornado plots) showed which assumptions actually drove the recommendation and which were just noise. The output was a clear, structured recommendation that could be explained to someone who had not built the model.</p>
      </div>

      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">Decision Analysis</span>
        <span class="pkj-project-skill-tag">Utility Functions</span>
        <span class="pkj-project-skill-tag">Sensitivity Analysis</span>
        <span class="pkj-project-skill-tag">Tornado Plots</span>
        <span class="pkj-project-skill-tag">Scenario Planning</span>
        <span class="pkj-project-skill-tag">Data Sourcing</span>
        <span class="pkj-project-skill-tag">Structured Recommendations</span>
      </div>

      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery">
        <div class="pkj-gallery-grid">
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072131.png" alt="Decision Model 1"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072148.png" alt="Decision Model 2"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072158.png" alt="Decision Model 3"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072210.png" alt="Decision Model 4"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BVR516/Screenshot 2026-05-26 072221.png" alt="Decision Model 5"></div>
        </div>
      </div>

    </div>

    <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/To Buy or Rent a Home as a New Grad - Project Report - 516.pdf" target="_blank" rel="noopener">
          <span class="pkj-pdf-icon">&#128196;</span>
          <div><span class="pkj-pdf-label">Full Project Report</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div>
        </a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">UW&ndash;Madison</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Course</span><span class="pkj-sidebar-row-value">ISyE 516</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">Academic</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Category</span><span class="pkj-sidebar-row-value">Industrial &amp; Systems</span></div>
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
