---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* Ph.D in Computational Science and Engineering, Georgia Institute of Technology, 2019.5 - now, advisor: Prof. [Edmond Chow](https://www.cc.gatech.edu/~echow/)
* M.S. in Computer Science, Georgia Institute of Technology, 2017.8 - 2019.5, advisor: Prof. Edmond Chow
* B.S. in Information and Computing Science, Sun Yat-sen University, 2013.8 - 2017.6, advisor: Dr. [Weicai Ye](https://www.researchgate.net/scientific-contributions/2033993793_Weicai_Ye) （叶纬材博士）

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Working Experience
* Research Intern, Intel Corporation 
  * 2020.8 - 2020.12
  * Supervisor: Dr. [Jeff Hammond](https://jeffhammond.github.io/)
* Graduate Research Assistant, Georgia Institute of Technology
  * 2018.1 - 2020.8
  * Supervisor: Prof. Edmond Chow
  * Performance optimization for computational chemistry applications
* Assistant Engineer, HPC Department of National Super-Computing Center in Shenzhen
  * 2015.8 - 2015.9
  * Supervisor: Dr. [Jianwen Liu](https://www.researchgate.net/profile/Jianwen_Liu) （刘建文博士）
  * Performance tuning for HPC applications (VASP, Amber)
  * Customer technical support
  
## Skills
* Programming Languages
  * Proficient: C, MATLAB
  * Can Google: C++11 or earlier, Fortran, Python, LaTeX
* Programming Framework
  * Proficient: OpenMP, MPI
  * Experienced: x86 intrinsic, CUDA, OpenCL
* Computer related:
  * Linux (used Linux distros: Ubuntu, CentOS, Arch) commands and git
  * Assembling my desktop hardware and hotwiring it



<!--
#Talks
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

#Teaching
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->