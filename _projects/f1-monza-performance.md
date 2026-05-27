---
layout: default
title: "Performative Statistics: Monza Circuit vs Overall Championship"
permalink: /projects/f1-monza-performance/
---
<div class="pkj-project-page">
  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Data Analytics &amp; ML</span>
    </div>
    <h1 class="pkj-project-title">Performative Statistics in Monza Circuit vs Overall Championship</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Course</strong>ISyE 649</div>
      <div class="pkj-meta-item"><strong>Advisor</strong>
        <a href="https://scholar.google.com/citations?user=14TnSJIAAAAJ&hl=en" target="_blank" rel="noopener">Dr. Tony McDonald</a>
      </div>
    </div>
  </div>
  <div class="pkj-project-layout">
    <div class="pkj-project-main">
      <div class="pkj-project-summary">
        <p>Monza is a power circuit. The teams that win at Monza are not always the teams that win championships. That gap was the starting point. Filtered and restructured multiple seasons of F1 race results, standings, and lap-time data to enable season-level vs track-specific performance comparisons.</p>
        <p>Applied abstraction and aggregation techniques to separate Monza-specific strengths from overall championship consistency. The answer was nuanced — some constructors showed strong Monza performance that did not carry through the season. Producing clear visualizations that made those patterns readable for a non-technical audience was the most interesting design challenge.</p>
      </div>
      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">Data Cleaning &amp; Aggregation</span>
        <span class="pkj-project-skill-tag">Abstraction &amp; Aggregation Design</span>
        <span class="pkj-project-skill-tag">Comparative Analysis</span>
        <span class="pkj-project-skill-tag">Visualization Storytelling</span>
        <span class="pkj-project-skill-tag">Analytical Reporting</span>
      </div>
      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery"><div class="pkj-gallery-grid">
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/Monza649/FastestLaps.png" alt="Fastest Laps Analysis"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/Monza649/Screenshot 2026-05-26 062641.png" alt="Monza Analysis 1"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/Monza649/Screenshot 2026-05-26 062705.png" alt="Monza Analysis 2"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/Monza649/Screenshot 2026-05-26 062731.png" alt="Monza Analysis 3"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/Monza649/Screenshot 2026-05-26 062750.png" alt="Monza Analysis 4"></div>
      </div></div>
    </div>
        <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/649 Project Report - Group 1.pdf" target="_blank" rel="noopener"><span class="pkj-pdf-icon">&#128196;</span><div><span class="pkj-pdf-label">Full Project Report</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div></a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">UW&ndash;Madison</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Course</span><span class="pkj-sidebar-row-value">ISyE 649</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">Academic</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Category</span><span class="pkj-sidebar-row-value">Data Analytics &amp; ML</span></div>
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