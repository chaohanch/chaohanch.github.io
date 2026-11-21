---
layout: page
title: Curriculum vitae
body_class: site-page cv-page
permalink: /cv
cv_file: CV_2026-11_web.pdf
---

{% assign cv_url = '/assets/files/' | append: page.cv_file | relative_url %}

<a class="cv-download" href="{{ cv_url }}" download>Download CV (PDF)</a>
<embed class="cv-preview" src="{{ cv_url }}" type="application/pdf" title="Curriculum vitae of {{ site.title | escape }}">
