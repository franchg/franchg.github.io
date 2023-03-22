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
* M.S. in Computer Science, University of Trento, 2016
* Ph.D in Computer Science, University of Trento, 2021
<!-- 
Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub -->
  
Skills
======
* Python Scientific Programming
  * Numpy / Scipy / Xarray
  * Dask / Ray
  * Jupyter
  * Voila dashboard
* Deep Learning
  * Pytorch / Lightning
  * WanDB / Tensorborad
  * Hydra
  * Optuna
* Spatial data analytics and GIS
  * PostGIS
  * GRASS / QGIS / GDAL
  * Eccodes / Cfgrib
* DevOps and MLOps
  * Backend web developement (Django / Flask / FastAPI)
  * Microsevices with Docker / docker-compose / Swarm
  * Proficient in PostgresSQL / PostGIS 
  * Git
  * GitLab CI/CD
  * Linux system administration (SystemD, bash scripting)
  * Monitoring (Sentry, Grafana)
* HPC
  * Slurm

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
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
