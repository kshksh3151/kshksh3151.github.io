---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D Department of Chemistry, Seoul Natioal University(SNU)                                   [2024.09 - ongoing]
* M.S. Department of Chemistry, Pohang University of Science and Technology(POSTECH)            [2023.08 - 2024.08]
* B.S. Undergraduate Studies, Daegu Gyeongbook Institution of Science and Technology(DGIST)     [2019.02 - 2023.08]

Skills
======
* Molecular Dynamics(MD) Simulation
  * All-atom MD simulation(OpenMM)
  * Coarse Grained MD simulation(HOOMD)
* Density Functional Theory
  * Gaussian
  * Multiwfn
* Python

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards & Scholarships
======
<ul>
{% for post in site.awardsNscholarships reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
