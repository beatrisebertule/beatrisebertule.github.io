---
layout: default
title: CV
description: Curriculum vitae
---

# Curriculum Vitae

<p class="lead">My CV is public — read it below or download the PDF.</p>

<div class="buttons">
  <a class="btn primary" href="{{ site.cv_pdf | relative_url }}" download>⬇ Download PDF</a>
  <a class="btn" href="{{ site.cv_pdf | relative_url }}" target="_blank" rel="noopener">Open in new tab</a>
</div>

<object class="pdf-frame" data="{{ site.cv_pdf | relative_url }}" type="application/pdf">
  <p class="muted">Your browser can't show the PDF here —
  <a href="{{ site.cv_pdf | relative_url }}">download it instead</a>.</p>
</object>
