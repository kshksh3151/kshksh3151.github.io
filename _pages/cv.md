---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-page" markdown="1">

## Education

- Integrated M.S./Ph.D. Department of Chemistry, Seoul National University (SNU) [2024.09 - ongoing]
- M.S. Department of Chemistry, Pohang University of Science and Technology (POSTECH) [2023.08 - 2024.08]
- B.S. Undergraduate Studies, Daegu Gyeongbook Institution of Science and Technology (DGIST) [2019.02 - 2023.08]

## Skills

- Molecular Dynamics (MD) Simulation
  - All-atom MD simulation (OpenMM)
- Density Functional Theory (DFT)
  - Gaussian, ORCA, Multiwfn
- Python

## Publications

<ul class="cv-list cv-publications">
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Awards & Scholarships

<ul class="cv-list">
{% for post in site.awardsNscholarships reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Talks

<ul class="cv-list">
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

## Teaching

<ul class="cv-list">
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

</div>