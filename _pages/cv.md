---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-page">

<div class="cv-section">

## Education

<ul class="cv-list">
  <li>Integrated M.S./Ph.D. Department of Chemistry, Seoul National University (SNU) [2024.09 - ongoing]</li>
  <li>M.S. Department of Chemistry, Pohang University of Science and Technology (POSTECH) [2023.08 - 2024.08]</li>
  <li>B.S. Undergraduate Studies, Daegu Gyeongbook Institution of Science and Technology (DGIST) [2019.02 - 2023.08]</li>
</ul>

</div>

<div class="cv-section">

## Skills

<ul class="cv-list">
  <li>
    Molecular Dynamics (MD) Simulation
    <ul>
      <li>All-atom MD simulation (OpenMM)</li>
    </ul>
  </li>
  <li>
    Density Functional Theory (DFT)
    <ul>
      <li>Gaussian, ORCA, Multiwfn</li>
    </ul>
  </li>
  <li>Python</li>
</ul>

</div>

<div class="cv-section">

## Publications

<ul class="cv-list cv-publications">
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

</div>

<div class="cv-section">

## Awards & Scholarships

<ul class="cv-list">
{% for post in site.awardsNscholarships reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

</div>

<div class="cv-section">

## Talks

<ul class="cv-list">
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

</div>

<div class="cv-section">

## Teaching

<ul class="cv-list">
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

</div>

</div>