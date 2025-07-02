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
* Direct Ph.D in Architecture (Urban climate), Zhejiang University (Co-supervised at ETH, Zurich), 2019-2025 (expected)
* B.S. in Mechanical engineering, Nanjing University of Science and technology, 2013-2017

Work experience
======
* 2017-2019: Wind power resource engineer
  * Zhejiang Windey Co., Ltd. (One of the top Wind turbine manufacturer in China)
  * Duties includes: responsible for site assessments, energy yield calculations, and micro-siting.

* 2019-2021: Research Assistant
  * Honkong University-Zhejiang Institute of Research and Innovation
  * Duties included: Establish and maintain urban climate observations database, Conduct statistical analysis. Coordinated and integrated research progress within the laboratory.
 
Skills
======
* Python
* Machine Learning
  * CNN-based satellite image recognation, land cover classification
  * Machine learning-based interpolatation
  * Physics-informed machine learning methods, Explainable machine learning techniques
* Mesoscale-climate simulations: WRF (Weather Research & Forecasting Model), Data assimilation, generate input data from GCM model runs.
* Microscale-climate simulations: SOLWEIG (SOlar and LongWave Environmental Irradiance Geometry model), Fluent
* Remote sensing image processing, GIS...

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
