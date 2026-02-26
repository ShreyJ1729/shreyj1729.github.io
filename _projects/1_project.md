---
layout: page
title: "GLAS: Global Landslide Analytics System"
description: "AI-driven landslide risk assessment using geophysical and meteorological data. ISEF 1st Grand Prize, $10k. Published at 2021 MIT URTC."
img: assets/img/thumbnail.png
importance: 1
category: work
---

**Shrey Joshi\*, Ishaan Javali\*, Dr. Ellen Rathje**

[Code](https://github.com/Landslide-Analytics-System) &nbsp;/&nbsp; [Poster](/assets/pdf/poster.pdf) &nbsp;/&nbsp; [IEEE Xplore](https://doi.org/10.1109/URTC54388.2021.9701628) &nbsp;/&nbsp; [Landslide Risk Map](/assets/img/susmap.png)

> **ISEF 1st Grand Prize, $10k won** — Accepted & published to 2021 MIT URTC

We introduce **GLAS**: a scalable, low-latency, Global Landslide Analytics System, along with the first publicly available dataset of **Global Landslide Incidents and Features (GLIF)**. GLIF consists of elevation, climate, lithology, forest change, and human infrastructure data for tens of thousands of landslide and non-landslide locations/times around the world. GLAS consists of Random Forest (RF) models trained on GLIF for three tasks: landslide forecasting (binary), landslide severity assessment (categorical), and landslide date estimation (categorical).

A new data-driven susceptibility mapping approach is derived using a weighted sum of static features and RF feature importances. We also demonstrate that historical multispectral LANDSAT-8 satellite data can be used to detect sudden changes in bare-earth exposure (Red Band: 655nm) and soil moisture (SWIR: Bands 5 & 7) to detect unreported rainfall-induced landslides, which could serve as additional training data by adding to GLIF's repository of landslide instances.

<div class="row justify-content-sm-center">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/susmap.png" title="Global Landslide Susceptibility Map" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Global Landslide Susceptibility Map generated using GLAS
</div>
