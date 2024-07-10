---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my full CV]()

Education
======
* Ph.D in Computer Engineering, University of Florida, 2018 
* M.S. in Computer Science, Clemson University, 2014
* B.S. in Computer Science, Minor in Mathematics, South Carolina State University, 2012

Work experience
======
* Current Appointment: Associate Professor
  * University of South Florida
  * Department of Computer Science and Engineering
 
* 2018 - 2024: Assistant Professor
  * University of South Florida
  * Department of Computer Science and Engineering

* 2013 - 2018: Research Assistant
  * Clemson University (Human-Centered Computing), University of Florida (Computer Engineering)
  * Supervisor: Professor Damon Woodard

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
