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
* Ph.D. in Physics, Indian Institute of Technology (IIT) Madras, India  
  * **Specialization:** Experimental high energy heavy ion physics  
  * **Experiment:** Compact Muon Solenoid (CMS), CERN  
  * **Duration:** 4 years and 11 months (July 7, 2018 – June 13, 2023)  
  * **Date of defense:** June 13, 2023  
  * **Thesis at CERN Document Server (CDS):** [https://repository.cern/records/42aqd-nww26](https://repository.cern/records/42aqd-nww26)  
  * **Supervisor:** Prof. Prabhat Ranjan Pujahari ([p.pujahari@iitm.ac.in](mailto:p.pujahari@iitm.ac.in))  


* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
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
<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======

All the talks I have presented are based on my own works, which are mentioned in selected publications. Talks where I was personally invited are marked with an **invited** label.

International talks
------
  <ul>{% for post in site.talks reversed %}
   {% if post.category == 'international' %}
     {% include archive-single-talk-cv.html  %}
   {% endif %}
  {% endfor %}</ul>

Nnational talks
------
  <ul>{% for post in site.talks reversed %}
   {% if post.category == 'national' %}
     {% include archive-single-talk-cv.html  %}
   {% endif %}
  {% endfor %}</ul>

Poster presentations
------
  <ul>{% for post in site.talks reversed %}
   {% if post.category == 'poster' %}
     {% include archive-single-talk-cv.html  %}
   {% endif %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams