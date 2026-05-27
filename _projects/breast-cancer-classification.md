---
layout: default
title: "Predictive Breast Cancer Classification in the U.S."
permalink: /projects/breast-cancer-classification/
---
<div class="pkj-project-page">
  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Data Analytics &amp; ML</span>
    </div>
    <h1 class="pkj-project-title">Predictive Breast Cancer Classification in the U.S.</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Course</strong>ISyE 521</div>
      <div class="pkj-meta-item"><strong>Advisor</strong>
        <a href="https://ari-smith-research.github.io/" target="_blank" rel="noopener">Dr. Ari Smith</a>
      </div>
    </div>
  </div>
  <div class="pkj-project-layout">
    <div class="pkj-project-main">
      <div class="pkj-project-summary">
        <p>Built and compared multiple machine learning approaches on a breast cancer diagnostic dataset. Logistic regression, KNN, and random forest were the supervised models. GridSearchCV handled hyperparameter tuning. StandardScaler handled preprocessing. K-Means clustering was added to explore structure in the data before throwing supervised models at it.</p>
        <p>The more interesting parts were not the final accuracy numbers. They were the moments where preprocessing choices visibly shifted model performance, and the exercise of communicating those tradeoffs clearly. A model that performs well but cannot be explained to a medical reviewer is not useful in context.</p>
      </div>
      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">Python</span>
        <span class="pkj-project-skill-tag">Scikit-learn</span>
        <span class="pkj-project-skill-tag">Logistic Regression</span>
        <span class="pkj-project-skill-tag">KNN</span>
        <span class="pkj-project-skill-tag">Random Forest</span>
        <span class="pkj-project-skill-tag">StandardScaler</span>
        <span class="pkj-project-skill-tag">GridSearchCV</span>
        <span class="pkj-project-skill-tag">K-Means Clustering</span>
        <span class="pkj-project-skill-tag">Model Evaluation</span>
      </div>
      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery"><div class="pkj-gallery-grid">
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BCC521/Screenshot 2026-05-26 071904.png" alt="Analysis 1"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BCC521/Screenshot 2026-05-26 071920.png" alt="Analysis 2"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BCC521/Screenshot 2026-05-26 071937.png" alt="Analysis 3"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BCC521/Screenshot 2026-05-26 071952.png" alt="Analysis 4"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BCC521/Screenshot 2026-05-26 072006.png" alt="Analysis 5"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BCC521/Screenshot 2026-05-26 072018.png" alt="Analysis 6"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/BCC521/Screenshot 2026-05-26 072032.png" alt="Analysis 7"></div>
      </div></div>
    </div>
        <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/Predictive Breast Cancer Classification in the U.S. - Project Report - 521.pdf" target="_blank" rel="noopener"><span class="pkj-pdf-icon">&#128196;</span><div><span class="pkj-pdf-label">Full Project Report</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div></a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">UW&ndash;Madison</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Course</span><span class="pkj-sidebar-row-value">ISyE 521</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">Academic</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Category</span><span class="pkj-sidebar-row-value">Data Analytics &amp; ML</span></div>
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