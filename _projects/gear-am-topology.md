---
layout: default
title: "Sustainable Gear Design via Topology Optimization & Generative Design"
permalink: /projects/gear-am-topology/
---
<div class="pkj-project-page">
  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-bt">B.Tech.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Manufacturing &amp; Mechanical</span>
    </div>
    <h1 class="pkj-project-title">Sustainable Gear Design via Topology Optimization &amp; Generative Design</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Degree</strong>B.Tech. Capstone</div>
      <div class="pkj-meta-item"><strong>Advisor</strong>
        <a href="https://scholar.google.com/citations?hl=en&user=jpvg7TIAAAAJ" target="_blank" rel="noopener">Dr. K. Palaksha Reddy</a>
      </div>
    </div>
  </div>
  <div class="pkj-project-layout">
    <div class="pkj-project-main">
      <div class="pkj-project-summary">
        <p>Started with a spur gear and one question: how much material can you remove before it fails? Ran topology optimization and generative design workflows in parallel using ANSYS Workbench and Autodesk Fusion 360, then compared the outputs against each other and the original baseline design.</p>
        <p>The goal was not just weight reduction. The designs had to work for metal additive manufacturing, so every material removal decision had to account for manufacturability — overhangs, support structures, and print orientation from the start.</p>
        <p>Final designs were evaluated on weight savings, stress distribution, estimated AM cost, and print time. Documenting those tradeoffs honestly was as important as finding the lightest geometry.</p>
      </div>
      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">SolidWorks (CAD)</span>
        <span class="pkj-project-skill-tag">ANSYS Workbench (FEA)</span>
        <span class="pkj-project-skill-tag">Autodesk Fusion 360</span>
        <span class="pkj-project-skill-tag">Topology Optimization</span>
        <span class="pkj-project-skill-tag">Generative Design</span>
        <span class="pkj-project-skill-tag">Design for AM (DfAM)</span>
        <span class="pkj-project-skill-tag">Metal AM Cost Estimation</span>
        <span class="pkj-project-skill-tag">Technical Report Writing</span>
      </div>
      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery"><div class="pkj-gallery-grid">
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/OG Design Isometric.jpg" alt="Original Design"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/Generative Design Spur Gear.jpg" alt="Generative Design"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/Topology Optimized Design.jpg" alt="Topology Optimized"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/GD Final Output.jpg" alt="GD Final Output"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/TO SW Final Model.jpg" alt="TO Final Model"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/FD1 Iso View.jpg" alt="Final Design 1"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/FD2 Iso View.jpg" alt="Final Design 2"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/FD3 Iso View.jpg" alt="Final Design 3"></div>
        <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/BTech Projects/GAMTO/Base Design.jpg" alt="Base Design"></div>
      </div></div>
    </div>
        <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/Final Draft Maxi Project Report - 9054 & 9199.docx.pdf" target="_blank" rel="noopener"><span class="pkj-pdf-icon">&#128196;</span><div><span class="pkj-pdf-label">Full Project Report</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div></a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">SASTRA University</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">B.Tech. Capstone</span></div><div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Category</span><span class="pkj-sidebar-row-value">Manufacturing &amp; Mechanical</span></div>
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