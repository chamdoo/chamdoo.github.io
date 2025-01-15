---
layout: default
title: "Home"
---

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.github.url }}/assets/profile.jpg" alt="Sungjin Lee">

I am an associate professor at [EECS, DGIST (Daegu Gyeongbuk Institute of Science and Technology)](eecs.dgist.ac.kr). Before joining DGIST in July 2017, I worked as an assistant professor at Inha University from March 2016 to June 2017. I was a postdoctoral associate in the [Computation Structures Group (CSG)](http://www.csg.csail.mit.edu/) at [MIT CSAIL](http://www.csail.mit.edu/) advised by Prof. Arvind. At MIT, I worked on the development of system software for high-performance storage systems, in particular, for non-volatile memory systems. I earned the PhD and MS degrees in computer science and engineering from the [Seoul National University (SNU)](http://snu.ac.kr/) in 2013 and 2007, respectively, and received the BE degree in electrical engineering from the Korea University in 2005. At SNU, I was a member of the [Computer Architecture and Embedded System Laboratory (CARES)](http://cares.snu.ac.kr/) led by Prof. Jihong Kim. My current research interests include system software, storage systems, operating systems, and embedded software.

#### Contact

- Email: [{{site.data.basic.email}}](mailto:{{site.data.basic.email}})
- Bibliography: [DBLP](https://dblp.uni-trier.de/pid/29/3671-1.html), [Google Scholar](https://scholar.google.com/citations?user=2Da8hHAAAAAJ&hl=en)
- Phone: {{site.data.basic.phone}}
- Office: {{site.data.basic.office}}, {{site.data.basic.institution_address}}

#### Education

- Postdoctoral Associate, Computer Science and Artificial Intelligence Laboratory (CSAIL), Massachusetts Institute of Technology (MIT), 2013 -- 2016
- Ph.D. in Computer Science and Engineering, Seoul National University, 2013
- M.S. in Computer Science and Engineering, Seoul National University, 2007
- B.E. in Electrical Engineering, Korea University, 2005

#### Experience

{% for section in site.data.experience %} 
- {{section.position}}, {{section.institution}}, {{section.period}} {% endfor %}

#### [Publication](https://scholar.google.com/citations?user=2Da8hHAAAAAJ&hl=en)
<br>

#### Honors and Awards
{% for section in site.data.awards %} 
- {{section.name}}, {{section.organization}}, {{section.year}} {% endfor %}

#### Service
{% for section in site.data.services %}
- {{section.role}}, {{section.organization}}, {{section.period}} {% endfor %}
