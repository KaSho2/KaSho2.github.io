---
layout: default
title: "Process Capability & Launch Readiness Copilot"
permalink: /projects/launch-readiness-copilot/
description: "Agentic AI decision-support for process stability and launch readiness review."
---

<div class="pkj-project-page">

  <div class="pkj-project-hero">
    <div class="pkj-project-badges">
      <span class="pkj-badge pkj-badge--level-ms">M.S.</span>
      <span class="pkj-badge pkj-badge--academic">Academic Project</span>
      <span class="pkj-badge pkj-badge--level-bt" style="background:var(--pkj-surface-alt);color:var(--pkj-navy)">Industrial &amp; Systems</span>
    </div>
    <h1 class="pkj-project-title">Process Capability &amp; Launch Readiness Copilot</h1>
    <div class="pkj-project-meta">
      <div class="pkj-meta-item"><strong>Full title</strong>EPD 522 Academic Capstone (not M.S. Thesis)</div>
      <div class="pkj-meta-item"><strong>Course</strong>EPD 522</div>
      <div class="pkj-meta-item"><strong>Advisors</strong>Dr. Rajakamal Gopinath &amp; Dr. Anthony Orzechowski</div>
      <div class="pkj-meta-item"><strong>Team</strong>Solo</div>
    </div>
  </div>

  <div class="pkj-project-layout">
    <div class="pkj-project-main">

      <div class="pkj-project-summary">
        <p>The question this project started with: can an AI system reliably reproduce what an engineer does when reviewing SPC data before a product launch? The short answer is: partially. That partial answer is actually the point.</p>
        <p>Built a pilot agentic workflow that takes process data, checks stability through control charts, computes capability indices (Cp, Cpk, Pp, Ppk), and writes a plain-language summary ready for both technical review and executive briefing. The system does not decide. It summarizes, flags, and hands back to the engineer. Human judgment stays in the loop by design.</p>
        <p>Scope was deliberately narrow: one dataset, no production integration, no external API calls to live manufacturing systems. Safety and reliability in a decision-support context matter more than coverage. The goal was a safe, trustworthy pilot that could be evaluated honestly, not an impressive demo that breaks in real conditions.</p>
      </div>

      <div class="pkj-proj-section-label">Skills</div>
      <div class="pkj-project-skills">
        <span class="pkj-project-skill-tag">SPC &ndash; Stability vs Capability Framing</span>
        <span class="pkj-project-skill-tag">Cp / Cpk / Pp / Ppk</span>
        <span class="pkj-project-skill-tag">Agentic Workflow Design</span>
        <span class="pkj-project-skill-tag">Azure AI</span>
        <span class="pkj-project-skill-tag">Human-in-the-Loop Design</span>
        <span class="pkj-project-skill-tag">Risk Controls</span>
        <span class="pkj-project-skill-tag">Technical Communication</span>
        <span class="pkj-project-skill-tag">Executive Memo Writing</span>
      </div>

      <div class="pkj-proj-section-label">Project Gallery</div>
      <div class="pkj-project-gallery">
        <div class="pkj-gallery-grid">
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/LRC522/Infographics of PCE.png" alt="Process Capability Infographic"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/LRC522/Infographics of PCE 2.png" alt="Process Capability Infographic 2"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/LRC522/Infographics of PCE 3.png" alt="Process Capability Infographic 3"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/LRC522/Screenshot 2026-05-26 062918.png" alt="Copilot Output 1"></div>
          <div class="pkj-gallery-item"><img class="pkj-gallery-img" src="/images/MS Projects/LRC522/Screenshot 2026-05-26 062938.png" alt="Copilot Output 2"></div>
        </div>
      </div>

    </div>

    <div class="pkj-project-sidebar">
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Read the full report</div>
        <a class="pkj-pdf-link" href="/assets/pdfs/Process Capability & Launch Readiness Copilot - Executive Slide Deck.pdf" target="_blank" rel="noopener">
          <span class="pkj-pdf-icon">&#128196;</span>
          <div><span class="pkj-pdf-label">Executive Slide Deck</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div>
        </a>
        <a class="pkj-pdf-link" href="/assets/pdfs/Process Capability & Launch Readiness Copilot - Tech Insights & Recommendations .pdf" target="_blank" rel="noopener">
          <span class="pkj-pdf-icon">&#128196;</span>
          <div><span class="pkj-pdf-label">Tech Insights &amp; Recommendations</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div>
        </a>
        <a class="pkj-pdf-link" href="/assets/pdfs/Summary Memo - 9082624322 (1).pdf" target="_blank" rel="noopener">
          <span class="pkj-pdf-icon">&#128196;</span>
          <div><span class="pkj-pdf-label">Summary Memo</span><span class="pkj-pdf-sub">PDF &middot; Opens in new tab</span></div>
        </a>
      </div>
      <div class="pkj-sidebar-card">
        <div class="pkj-sidebar-label">Project info</div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Institution</span><span class="pkj-sidebar-row-value">UW&ndash;Madison</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Course</span><span class="pkj-sidebar-row-value">EPD 522</span></div>
        <div class="pkj-sidebar-row"><span class="pkj-sidebar-row-label">Type</span><span class="pkj-sidebar-row-value">Academic &middot; Course Capstone</span></div>
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
