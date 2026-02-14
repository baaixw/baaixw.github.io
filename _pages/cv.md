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
* *[Update with your degree, university, and year]*
* *[Update with your degree, university, and year]*

Work Experience
======
* **Researcher**, The Hong Kong Polytechnic University
  * *[Update with your role details and dates]*

Skills
======
* *[Update with your skills]*

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
  
Service and Leadership
======
* *[Update with your service and leadership roles]*
