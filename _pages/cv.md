---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
description: Last updated September 2026.
---

<p>
  <a class="btn btn-sm z-depth-0" role="button" href="{{ '/assets/pdf/RikiShimizu_CV.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">
    <i class="fa-solid fa-file-pdf"></i> Download PDF
  </a>
</p>

<div class="cv-embed">
  <object data="{{ '/assets/pdf/RikiShimizu_CV.pdf' | relative_url }}" type="application/pdf" width="100%" height="100%">
    <p>
      Your browser cannot display PDFs inline.
      <a href="{{ '/assets/pdf/RikiShimizu_CV.pdf' | relative_url }}">Download the PDF instead.</a>
    </p>
  </object>
</div>

<style>
  .cv-embed {
    width: 100%;
    height: 85vh;
    min-height: 600px;
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    overflow: hidden;
  }
  /* Inline PDF viewers are unreliable on mobile; show the download link instead. */
  @media (max-width: 768px) {
    .cv-embed {
      height: auto;
      min-height: 0;
      border: none;
    }
    .cv-embed object {
      display: none;
    }
    .cv-embed p {
      display: block;
    }
  }
</style>
