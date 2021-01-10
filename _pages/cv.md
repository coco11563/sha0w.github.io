---
layout: archive
permalink: /cv
author_profile: true
title: "Sha0w's Curriculum Vitae"
excerpt: "About me"
author_profile: true
redirect_from:
  - /resume
  - /cv/
  - /
---

{% include base_path %}

---

Education
======
* B.S. in Geographic Information System, East China University of Technology, 2011 - 2015
* M.S. in Software Engineering, China University of Geosciences Wuhan, 2015 - 2018
* Ph.D in Computer Science , University of Chinese Academy of Sciences, 2019 - now

---

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

---

Work experience
======
* June 2018-August 2019: Big data development engineer
  * Computer Network Information Center, Chinese Academy of Sciences (Beijing)
  * Project Name: National Natural Science Foundation of China Big Data Knowledge Management Service Platform (Phase II)
  * Duties included: 
    * Spark implementation of Peking University's keyword algorithm
    * This work has been applied to the keywords recommendation of the various academic departments of the NSFC project application in 2020
  * Supervisor: [Yuanchun Zhou](http://people.ucas.ac.cn/~zhouyuanchun)
  * Keywords : **Spark**, **Neo4j**, **Piflow**, Scala
* June 2017-Dec 2017: Big data development engineer (**internship**)
  * Computer Network Information Center, Chinese Academy of Sciences (Beijing)
  * Project Name: National Natural Science Foundation of China Big Data Knowledge Management Service Platform (GC-FG4161781)
  * Duties included: 
    * Reconstruction of the database and front-end display system of scientific researchers, achievements, research institutions, and migration to a distributed file system and database based on the Hadoop platform.
    * Responsible for cleaning the data flow during the migration process from the Oracle database to the Hive data warehouse.  
  * Supervisor: [Du Yi](http://people.ucas.ac.cn/~duyi)
  * Keywords : ETL, **Spark**, Scala, Java, **Nifi**, **Hive**, Oracle
  
---

Portfolio
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single.html %}
  {% endfor %}</ul>

[comment]: <> (Teaching)

[comment]: <> (======)

[comment]: <> (  <ul>{% for post in site.teaching %})

[comment]: <> (    {% include archive-single-cv.html %})

[comment]: <> (  {% endfor %}</ul>)
  
[comment]: <> (Service and leadership)

[comment]: <> (======)

[comment]: <> (* Currently signed in to 43 different slack teams)
