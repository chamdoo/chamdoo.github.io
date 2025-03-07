---
layout: default
title: "Home"
---

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.github.url }}/assets/profile.jpg" alt="Sungjin Lee">

I am an Associate Professor at [CSE, Pohang University of Science and Technology (POSTECH)](https://cse.postech.ac.kr/), where I am leading [Computer Architecture and Operating Systems (CAOS) Laboratory](https://www.caos.postech.ac.kr/) together with Prof. [Jisung Park](https://jisung-park.github.io/). Before joining POSTECH in March 2025, I worked as an associate professor at DGIST (from July 2017 to February 2025) and an assistant professor at Inha University (from March 2016 to June 2017), respectively. I was a postdoctoral associate in the [Computation Structures Group (CSG)](http://www.csg.csail.mit.edu/) at [MIT CSAIL](http://www.csail.mit.edu/) advised by Prof. Arvind. At MIT, I worked on the development of system software for big-data analytic systems and non-volatile memory systems. I earned the PhD and MS degrees in computer science and engineering from the [Seoul National University (SNU)](http://snu.ac.kr/) in 2013 and 2007, respectively, and received the BE degree in electrical engineering from the Korea University in 2005. At SNU, I was a member of the [Computer Architecture and Embedded System Laboratory (CARES)](http://cares.snu.ac.kr/) led by Prof. Jihong Kim. My current research interests include operating systems, system software, storage/memory systems, and AI systems.
<br/>
<br/>

#### Contact

- Email: [{{site.data.basic.email}}](mailto:{{site.data.basic.email}})
- Phone: {{site.data.basic.phone}}
- Office: {{site.data.basic.office}}, {{site.data.basic.institution_address}}

#### Academic Employment

{% for section in site.data.experience %} 
- {{section.position}}, {{section.institution}}, {{section.period}} {% endfor %}

#### Education

- Postdoctoral Associate, Computer Science and Artificial Intelligence Laboratory (CSAIL), Massachusetts Institute of Technology (MIT), 2013 -- 2016
- Ph.D. in Computer Science and Engineering, Seoul National University (SNU), 2013
- M.S. in Computer Science and Engineering, Seoul National University (SNU), 2007
- B.E. in Electrical Engineering, Korea University, 2005

#### Publication
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=2Da8hHAAAAAJ&view_op=list_works&sortby=pubdate), [DBLP](https://dblp.uni-trier.de/pid/29/3671-1.html)

#### Awards and Fellowships
{% for section in site.data.awards %} 
- {{section.name}}, {{section.organization}}, {{section.year}} {% endfor %}

#### Students
- **Postdoc**  
  * Jinhyung Koo @CSE/POSTECH (2025.03~)
  * Junsu Im @CSE/POSTECH (2025.03~)
- **Ph.D Student**
  * Minjae Kim @EECS/DGIST (2019.02~)
  * Juhyung Park @EECS/DGIST (2020.02~)
  * Jungwoo Kim @EECS/DGIST (2021.02~)
  * Seonggyun Oh @EECS/DGIST (2021.02~)
  * Euntae Bae @EECS/DGIST (2022.02~)
  * Jeeyun Kim @CSE/POSTECH (2022.02~)
- **MS Student**
  * Chanwoo Moon @EECS/DGIST (2024.03~) 
  * Gwangin Kim @EECS/DGIST (2024.03~)
  * Kyeongmin Kim @EECS/DGIST (2024.03~)
  * Jueun Park @EECS/DGIST (2024.03~)
  * Jaeheon Lee @CSE/POSTECH (2025.03~)
  * Heejin Kim @CSE/POSTECH (2025.03~)

#### Academic Services
{% for section in site.data.services %}
- {{section.role}}, {{section.organization}}, {{section.period}} {% endfor %}
