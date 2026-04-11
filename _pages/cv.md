---
layout: default
permalink: /cv/
title: cv
nav: true
nav_order: 5
---

<div class="post">
  <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
    <p class="post-description">
      <a href="{{ '/assets/pdf/Schumacher_CV.pdf' | relative_url }}" target="_blank" class="btn btn-primary">
        <i class="fas fa-file-pdf"></i> Download CV (PDF)
      </a>
    </p>
  </header>

  <article>
    <div class="cv">
      <embed src="{{ '/assets/pdf/Schumacher_CV.pdf' | relative_url }}" type="application/pdf" width="100%" height="800px" />
    </div>
  </article>
</div>
