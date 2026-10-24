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

  <h2>Education</h2>

  <ul class="cv-list">
    <li>Integrated M.S./Ph.D. Department of Chemistry, Seoul National University (SNU) [2024.09 - ongoing]</li>
    <li>M.S. Department of Chemistry, Pohang University of Science and Technology (POSTECH) [2023.08 - 2024.08]</li>
    <li>B.S. Undergraduate Studies, Daegu Gyeongbook Institution of Science and Technology (DGIST) [2019.02 - 2023.08]</li>
  </ul>


  <h2>Skills</h2>

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


  <h2>Publications</h2>

  <ul class="cv-list cv-publications">
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>


  <h2>Awards &amp; Scholarships</h2>

  <ul class="cv-list">
    {% for post in site.awardsNscholarships reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>


  <h2>Talks</h2>

  <ul class="cv-list">
    {% for post in site.talks reversed %}
      {% include archive-single-talk-cv.html %}
    {% endfor %}
  </ul>


  <h2>Teaching</h2>

  <ul class="cv-list">
    {% for post in site.teaching reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>

</div>