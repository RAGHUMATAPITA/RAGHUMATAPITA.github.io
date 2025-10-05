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
* **Doctor of Philosophy (Ph.D.) in Physics, Indian Institute of Technology (IIT) Madras, Chennai, Tamilnadu, India**  
  * **Specialization:** Experimental high energy heavy ion physics  
  * **Experiment:** Compact Muon Solenoid (CMS), CERN  
  * **Duration:** 4 years and 11 months (July 7, 2018 – June 13, 2023)  
  * **Date of defense:** June 13, 2023  
  * **Thesis at CERN Document Server (CDS):** [https://repository.cern/records/42aqd-nww26](https://repository.cern/records/42aqd-nww26)  
  * **Supervisor:** [Prof. Prabhat Ranjan Pujahari](https://physics.iitm.ac.in/people/facultyinfo/prabhatpujahari.html) ([p.pujahari@iitm.ac.in](mailto:p.pujahari@iitm.ac.in))  

* **Master in Science (M.Sc.), Utkal University, Bhubaneswar, Odisha, India**  
  * **Specialization:** High energy physics
  * **Other courses:** Advanced particle physics and filed theory-I, Advanced particle physics and filed theory-II, Quantum mechanics-I, Quantum mechanics-II, Advanced quantum mechanics, Classical mechanics, Mathematical method in physics, Statistical mechanics, Basics condensed matter physics, Electronics, Basic electronics
  * **Duration:** 2 years (2016 – 2018)
  * **First Class with Distinction (86.5%, CGPA: 9.08)**
  * **Master project:** Calibration of scintillator detectors for measurement of cosmic ray showers
    * **Experiment:** GRAPES-3, Tata Institue Of Fundamental Research (TIFR), OOTY, India
    * **Supervisor:** [Prof. Prabhat Kumar Mohanty](https://scholar.google.com/citations?user=Eu4IhOUAAAAJ&hl=en) ([pkm@tifr.res.in](mailto:pkm@tifr.res.in))

* **Bachelor in Science (B.Sc.), Fakir Mohan University, U.N. College, Soro, Balasore, Odisha, India**
  * **Specialization:** Physics
  * **Minor:** Mathematics and Chemistry
  * **Other courses:** English, Odia, Environmental Science, Biology
  * **Duration:** 3 years (2013 – 2016)
  * **First Class with Distinction (91.8% honors, 78.16% aggregate)**

* **Intermediate in Science (I.Sc.), Sahid Memorial College, Manida, Mayurbhanj, Odisha, India**
  * **Council of Higher Secondary Education, Odisha**
  * **Class:** 11th - 12th
  * **Courses:** Physics, Chemistry, Math, Biology, English, Odia
  * **Minor:** Mathematics and Chemistry
  * **Duration:** 2 years (2011 – 2013)
  * **First Class with 80.33%**

* **Jaleswar High School, Jaleswar, Baleswar, Odisha, India**
  * **Board of Secondary Education, Odisha**
  * **Class:** 8th - 10th (2008 - 2011)
  * **First Class with 72.33%**
  
Work experience
======
* June 2023 - present: Postdoctoral researcher
  * University of Illinois, Chicago
  * Department of Physics, 845 W. Taylor St., Chicago, IL 60607, USA
  * Duties includes:
    * Analysis on jet wake effect in dijet events with the CMS experiment
    * Analysis on charged-particle suppression in oxygen-oxygen collisions
    * Analysis on charged-particle suppression in neon-neon collisions	
    * Anslysis on jet axis-based inclusive jet substructure measurement using Pythia dijet events and constraining color-charge effects of partonic energy loss
    * Analysis on jet axis decorrelation in dijet events with the CMS experiment
    * CMS heavy-ion tracking convener
    * CMS heavy-ion tracking validator
    * Helping to supervise students
  * Supervisor: [Prof. Olga Evdokimov](https://phys.uic.edu/profiles/evdokimov-olga/) ([evdolga@uic.edu](mailto:evdolga@uic.edu))
  
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
All of my publications can be found associated with my [InspireHEP author profile]({{ site.author.inspirehep }}).
Below, I list only the publications in which I am the sole contributor and/or have been directly involved.

Journal articles
------
  <ul>{% for post in site.publications reversed %}
   {% if post.category == 'manuscripts' %}
     {% include archive-single-cv.html  %}
   {% endif %}
  {% endfor %}</ul>

Conference proceedings
------
  <ul>{% for post in site.publications reversed %}
   {% if post.category == 'conferences' %}
     {% include archive-single-cv.html  %}
   {% endif %}
  {% endfor %}</ul>
  
Talks
======
All the talks I have presented are based on my own works, which are mentioned in [selected publications](/publications). Talks where I was personally invited are marked with an **invited** label.

International talks
------
  <ul>{% for post in site.talks reversed %}
   {% if post.category == 'international' %}
     {% include archive-single-talk-cv.html  %}
   {% endif %}
  {% endfor %}</ul>

National talks
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