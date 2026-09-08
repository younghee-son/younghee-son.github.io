---
layout: archive
title: "CV/Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
---

<style>
  .career-documents {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1.5rem;
  }
  .career-documents section { min-width: 0; }
  .career-documents h2 { margin-top: 0; }
  .career-documents object {
    display: block;
    width: 100%;
    height: 800px;
    border: 1px solid var(--global-border-color);
  }
  @media (max-width: 767px) {
    .career-documents { grid-template-columns: minmax(0, 1fr); }
    .career-documents object { height: 65vh; min-height: 400px; }
  }
</style>

<div class="career-documents">
  <section aria-labelledby="resume-heading">
    <h2 id="resume-heading">Resume</h2>
    <p><a href="{{ '/files/resume.pdf' | relative_url }}" download>Download resume (PDF)</a></p>
    <object data="{{ '/files/resume.pdf' | relative_url }}#view=FitH" type="application/pdf" aria-label="Resume PDF preview">
      <p>Your browser can't display PDFs inline. <a href="{{ '/files/resume.pdf' | relative_url }}">Open the resume (PDF)</a>.</p>
    </object>
  </section>
  <section aria-labelledby="cv-heading">
    <h2 id="cv-heading">CV</h2>
    <p><a href="{{ '/files/cv.pdf' | relative_url }}" download>Download CV (PDF)</a></p>
    <object data="{{ '/files/cv.pdf' | relative_url }}#view=FitH" type="application/pdf" aria-label="CV PDF preview">
      <p>Your browser can't display PDFs inline. <a href="{{ '/files/cv.pdf' | relative_url }}">Open the CV (PDF)</a>.</p>
    </object>
  </section>
</div>
