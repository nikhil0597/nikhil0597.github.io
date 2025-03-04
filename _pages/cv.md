---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Mathematics, IISER Thiruvananthapuram, (ongoing)
* M.Sc. in Mathematics, Cochin University of Science and Technology, 2020
* B.Sc. in Mathematics, St. Berchmans College, 2018

Work experience
======
* Summer 2018: Internship
  * Chennai Mathematical Institute, India
  * Supervisor: Dr. Manoj Kummini

* Summer 2019: Internship
  * Chennai Mathematical Institute, India
  * Supervisor: Prof. R Sridharan
  
Skills
======
* Mathematical analysis
* Coding
  * Python
  * C++
  * Matlab

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
