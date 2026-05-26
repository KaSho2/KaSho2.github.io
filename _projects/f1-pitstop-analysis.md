---
layout: default
title: "F1 Pit Stop Analysis"
permalink: /projects/f1-pitstop-analysis/
description: "Analyzed F1 pit stop performance trends across teams and seasons using RStudio and Tableau."
---

<div class="pkj-project-page">

  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Data Analytics &amp; ML</span>
    </div>
    <h1 class="pkj-project-title">F1 Pit Stop Analysis</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Course</strong>ISyE 412</div>
      <div class="pkj-meta-item"><strong>Advisor</strong>Dr. Tina Xu</div>
      <div class="pkj-meta-item"><strong>Team</strong>
        <a href="https://www.linkedin.com/in/najla-alkhathlan/" target="_blank" rel="noopener">Najla Alkhathlan</a>,
        <a href="https://www.linkedin.com/in/avery-finck-74251a24b/" target="_blank" rel="noopener">Avery Finck</a>,
        <a href="https://www.linkedin.com/in/albert-liang-372832302/" target="_blank" rel="noopener">Zhaoqi Liang</a>
      </div>
    </div>
  </div>

  <div class="pkj-project-layout">
    <div class="pkj-project-main">

      <div class="pkj-project-summary">
        <p>Pit stop data tells a story about more than just tire changes. The time lost, the consistency across a race weekend, and the patterns across a season reveal a lot about team operations and strategic priorities. This project cleaned and restructured multi-season F1 pit stop datasets in RStudio, built Tableau dashboards to surface those patterns, and defined KPIs that captured strategic advantage rather than raw speed.</p>
        <p>The goal was to make the analysis scannable and useful, not just accurate. A pit stop dashboard that requires a statistician to interpret it is not a useful tool for the person making race strategy decisions. Getting that balance right was the real challenge.</p>
      </div>

      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">RStudio</span>
        <span class="pkj-project-skill-tag">Tableau</span>
        <span class="pkj-project-skill-tag">Data Cleaning &amp; Reshaping</span>
        <span class="pkj-project-skill-tag">Visualization Design</span>
        <span class="pkj-project-skill-tag">KPI Definition</span>
        <span class="pkj-project-skill-tag">Analytical Reporting</span>
        <span class="pkj-project-skill-tag">Storytelling with Data</span>
      </div>

      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery">
        <div class="pkj-gallery-grid">
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071318.png" alt="Pit Stop Analysis 1"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071335.png" alt="Pit Stop Analysis 2"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071355.png" alt="Pit Stop Analysis 3"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071413.png" alt="Pit Stop Analysis 4"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071428.png" alt="Pit Stop Analysis 5"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071444.png" alt="Pit Stop Analysis 6"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071500.png" alt="Pit Stop Analysis 7"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071515.png" alt="Pit Stop Analysis 8"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/PS412/Screenshot 2026-05-26 071532.png" alt="Pit Stop Analysis 9"></div>
        </div>
      </div>

    </div>

    <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/F1 Pit Stop Analysis - Project Report - 412.pdf" target="_blank" rel="noopener">
          <span class="pkj-pdf-icon">&#128196;</span>
          <div><span class="pkj-pdf-label">Full Project Report</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div>
        </a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">UW&ndash;Madison</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Course</span><span class="pkj-sidebar-row-value">ISyE 412</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">Academic</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Category</span><span class="pkj-sidebar-row-value">Data Analytics &amp; ML</span></div>
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
