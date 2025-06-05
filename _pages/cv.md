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
* Ph.D. in Statistics, Bocconi University, 2024 
* M.S. in Statistical, Financial and Actuarial Sciences, Università di Firenze, 2019
* B.S. in Statistics, Università di Firenze, 2017

Work experience
======
* Winter 2025: Industry Internship,
  * SchainResearch, Stockholm, Sweden
  * Duties includes: data analysis, R programming, project management
    
* Autumn 2023: Research Assistant,
  * Karolinska Insitutet, Stockholm, Sweden
  * Duties includes: statistical methods and models development, R programming

* Autumn 2020 - Spring 2023: Teaching Assistant,
  * Bocconi University, Milan, Italy
  * Duties includes: Laboratories in class, student tutoring

* Autumn 2018 - Autumn 2019: Junior University Tutor,
  * Università di Firenze, Florence, Italy
  * Duties includes: Laboratories in class, student tutoring
  
Skills
======
  * IT Skills: (very good) R, LaTeX, (good) Python, Stata, SAS, Github, Matlab, Word, Excel, Power point, (fairly good) Java, SQL.
  * Language Skills: (mother tongue) Italian, (IELTS Certification C1 level) English, (basics) French, Spanish, Swedish.

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
