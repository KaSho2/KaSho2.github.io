---
layout: default
title: "Can We Predict if a Shipment Will Be On Time?"
permalink: /projects/shipment-ontime-prediction/
---
<div class="pkj-project-page">
  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Data Analytics &amp; ML</span>
    </div>
    <h1 class="pkj-project-title">Can We Predict if a Shipment Will Be On Time?</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Course</strong>ISyE 604</div>
      <div class="pkj-meta-item"><strong>Advisor</strong>
        <a href="https://scholar.google.com/citations?user=rNDml4YAAAAJ&hl=en" target="_blank" rel="noopener">Dr. Andi Wang</a>
      </div>
    </div>
  </div>
  <div class="pkj-project-layout">
    <div class="pkj-project-main">
      <div class="pkj-project-summary">
        <p>Logistics data has a lot of signal if you know where to look. Cleaned and engineered features from a structured shipment dataset, trained logistic regression and decision tree classifiers, and tuned with GridSearchCV. The interesting part was what came after the modeling.</p>
        <p>The focus was on building a clear narrative around the results: what does the model actually tell you, where does it fall short, and what would a logistics manager do with this information in practice? Reporting accuracy without context is not useful.</p>
      </div>
      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">Python</span>
        <span class="pkj-project-skill-tag">Pandas / NumPy</span>
        <span class="pkj-project-skill-tag">Scikit-learn</span>
        <span class="pkj-project-skill-tag">Logistic Regression</span>
        <span class="pkj-project-skill-tag">Decision Trees</span>
        <span class="pkj-project-skill-tag">GridSearchCV</span>
        <span class="pkj-project-skill-tag">Feature Engineering</span>
        <span class="pkj-project-skill-tag">Classification Metrics</span>
      </div>
      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery"><div class="pkj-gallery-grid">
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/SOP604/Screenshot 2026-05-26 063224.png" alt="Shipment Prediction 1"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/SOP604/Screenshot 2026-05-26 063240.png" alt="Shipment Prediction 2"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/SOP604/Screenshot 2026-05-26 063309.png" alt="Shipment Prediction 3"></div>
      </div></div>
    </div>
        <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/Can We Predict if a Shipment Will be On Time - Project Presentation 604.pdf" target="_blank" rel="noopener"><span class="pkj-pdf-icon">&#128196;</span><div><span class="pkj-pdf-label">Project Slides</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div></a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">UW&ndash;Madison</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Course</span><span class="pkj-sidebar-row-value">ISyE 604</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">Academic &middot; Solo</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Category</span><span class="pkj-sidebar-row-value">Data Analytics &amp; ML</span></div>
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