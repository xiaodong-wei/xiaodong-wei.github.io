---
layout: archive
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

## 1. Simulaiton-aware solid modeling
![](/images/engine-mount.gif){:width="300px" .align-left}  
In this work, we build smooth volume models that can be directly used in computer simulation. Such a model not only describes the shape of an object, but also discretizes its interior domain in a smooth manner, thus immediately suitable for simulations based on "bulk" geometries. Moreover, as all the simulation-related properties are already built in such geometric models, it allows downstream simulations to follow a standard procedure, and thus it is of great ease to link with commercial finite element packages such as LS-DYNA.
<br/><br/><br/><br/><br/><br/>

## 2. Material transport in neuronal branches
![](/images/transport.gif){:width="300px" .align-left}  
In this work, we study how traffic of material transport is routed and balanced in a complex geometry of a neurite network. A detailed knowledge through simulation of the traffic phenomenon is crucial to elucidating how neurons operate their material transport systems and, more importantly, to understanding and controlling the structure and function of neurons.
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

## 3. Medical image registration
![](/images/brain.gif){:width="300px" .align-left}  
In this work, we develop an advanced image registration technique to reveal detailed intermediate states between the two acquisition of two images, a source image representing the initial state and a target image representing the final state. Registration involves spatially aligning the two images and finding a correspondence such that monitoring a continuous change is possible. In particular, we apply the technique to monitor the changes after surgical removal of a brain tumor.
<br/><br/><br/><br/><br/><br/>

## 4. Adaptivity on smooth complex geometries
![](/images/adaptive.gif){:width="300px" .align-left}  
In this work, we explore to enable adaptivity on smooth, complex geometries. While objects in engineering and biomedicine are often complex-shaped, developing adaptivity schemes on such geometries is a challenge especially when a smooth representation is involved. Adaptivity, via local mesh refinement, is designed to locally and automatically "adapt" to where large error is expected. In this way, adaptivity can significantly enhance numerical accuracy without increasing much computational burden. This is especially beneficial in large-scale simulation that needs an enormous number of degrees of freedom.


