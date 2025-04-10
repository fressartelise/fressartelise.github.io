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
* 2024-     PhD, [CMAP](https://cmap.ip-paris.fr/), Ecole polytechnique and [Thales](https://www.thalesgroup.com/en)
  * Quantum computing for electromagnetic simulations
* 2022-2023 Mathematics and Applications Master's degree, Sorbonne Université
  * [Mathematics of Modelling speciality](https://www.ljll.fr/MathModel/index_en.html)
* Engineering degree (2019-2023), [École nationale des ponts et chaussées](https://ecoledesponts.fr/en)
  * Applied mathematics and computer science department
* 2017-2019 Preparatory classes MPSI-MP, Lycée Blaise Pascal, Orsay 
* 2014-2017 High school, Lycée Camille Claudel, Palaiseau

Work experience
======
* 01/2024-        PhD, [CMAP](https://cmap.ip-paris.fr/), Ecole polytechnique and [Thales](https://www.thalesgroup.com/en)
  * Quantum computing for electromagnetic simulations
  * Supervisors: Marc Massot, Michel Nowak, Nicole Spillane

* 10/2023-12/2023 Fixed-term contract, [Thales](https://www.thalesgroup.com/en)
  * quantum algorithm based on Monte Carlo, quantum importance sampling

* 04/2023-09/2023 Internship, [Thales](https://www.thalesgroup.com/en)
  * adaptive mesh refinement based on a posteriori error estimation, elctromagnetic simulations, quantum algorithms

* 03/2022-07/2022 Internship, [Karlsruhe Institute of Technology](https://www.math.kit.edu/ianm/en), Germany
  * multiscale method, numerical scheme

* 06/2021-12/2021 Internship, [CEA](https://www.cea.fr/english)
  * implementation of quasi-static Particle In Cell (PIC) models

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

<!--- 
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->