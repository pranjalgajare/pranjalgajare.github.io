---
title: "CV"
#permalink: /cv/ # You might remove or comment this out as the page will redirect
redirect_from:
  - /cv/ # This will be the path on your site that triggers the redirect
  - /resume # This will also redirect to your Google Drive CV
redirect_to: 'https://drive.google.com/file/d/1CLgVOw_g_CTK3ibXIxqhJ9lVT-CtSCiQ/view?usp=sharing'
author_profile: true # Probably not needed if it's just a redirect
---

{% include base_path %}

Education
======
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
