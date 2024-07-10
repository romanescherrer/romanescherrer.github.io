---
page_id: project_1
layout: page
title: Digital Holography
description: Enhancing Plankton Monitoring with AI
img: assets/img/project1/holo.jpg
importance: 1
category: work
related_publications: false
---

---

> ## Informations
>
> ---
>
> - `Project type`: Thesis
> - `Role`: PhD Student
> - `Period`: 2020-2023
> - `Partners`: ISEA, IRD, IFREMER
> - `Research Themes` : object detection, tracking, classification, instance segmentation, image reconstruction, generative models, 3D imaging.

## Overview

---

#### `Plankton: A Vital Resource to Monitor`

Water, a vital resource, harbors exceptional biodiversity, dominated by plankton which represents more than 98% of marine biomass. Plankton is crucial for the food chain and climate, producing more than half of the Earth's oxygen and absorbing a large part of carbon dioxide. However, its decline since the second industrial revolution threatens life on Earth, making the study of its abundance and distribution crucial for the preservation of marine ecosystems. Additionally, some species of plankton produce toxins that contaminate marine resources, posing risks to human health. Thus, regular monitoring of plankton is essential to ensure food security and public health.

#### `Traditional Methods and Their Limitations`

Traditional methods of studying plankton, using nets, sampling bottles, or pumps, are laborious and often damage fragile organisms. These manual techniques are insufficient to fully understand the planktonic ecosystem, requiring more efficient and automated methods.

Optical and holographic imaging instruments such as SIPPER, ISIIS, IFCB, and LISST-Holo2 have been developed to analyze plankton in situ and in the laboratory. These devices allow the study of particles of various sizes, deployed on different platforms like ROVs, fixed moorings, and AUVs. However, these devices are generally very expensive, energy-consuming, and cannot be deployed on a large scale. Additionally, the amount of data produced by these systems is such that only advanced computer vision methods can effectively process them.

#### `Towards a Low-Cost Monitoring System`

To multiply study areas, it is necessary to have instruments that are both efficient and inexpensive. Digital holography, requiring a light source and a camera, offers low-cost instruments with a large depth of field, allowing the imaging of microscopic objects without damaging them.
However, processing holograms is complex and requires iterative algorithms, often difficult to achieve in real-time on low-power embedded systems. Although deep learning methods offer solutions for hologram classification, their integration into in situ systems remains a challenge due to computational and storage constraints.

#### `Research Contributions`

This research project covers the design of the holographic instrument, the creation of new processing pipelines, and deep learning models adapted to holography, meeting end-user constraints and promoting the evolution of planktonic imaging devices.

# Associated Articles

<div class="publications">

{% bibliography -q @*[project=phd] %}

</div>
