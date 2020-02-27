---
layout: single
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

My research focuses on developing novel simulation-aware geometric modeling techniques for free-form, complex-shaped surfaces/volumes, 
motivated to address grand challenges in modern engineering design/optimization, computational biomedicine, and additive manufacturing. 
The related fundamental methods belong to the family of isogeometric analysis.

Simulaiton-aware solid modeling
-------------------------------
![](/images/engine-mount.gif =200x)  
In this work, we build smooth volume models that can be directly used in computer simulation. Such a model not only describes the shape of an object, but also discretizes its interior domain in a smooth manner, thus immediately suitable for simulations based on "bulk" geometries. Moreover, as all the simulation-related properties are already built in such geometric models, it allows downstream simulations to follow a standard procedure, and thus it is of great ease to link with commercial finite element packages such as LS-DYNA.
