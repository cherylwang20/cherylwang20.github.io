---
layout: page
title: Gallery
permalink: /gallery/
description: Snapshots with my research group and from conferences and travel.
nav: true
nav_order: 2
---

<style>
  .gallery-hero figure { margin-bottom: 0.35rem; }
  .gallery-hero img {
    width: 100%;
    max-height: min(72vh, 640px);
    object-fit: cover;
    border-radius: 0.25rem;
  }
  .gallery-row-equal figure { margin-bottom: 0.35rem; }
  .gallery-row-equal figure picture { display: block; }
  .gallery-row-equal img {
    width: 100%;
    height: 240px;
    object-fit: cover;
    border-radius: 0.25rem;
  }
  @media (min-width: 768px) {
    .gallery-row-equal img { height: 280px; }
  }
  .gallery-summer figure { margin-bottom: 0.35rem; }
  .gallery-summer img {
    width: 100%;
    max-height: 520px;
    object-fit: cover;
    border-radius: 0.25rem;
  }
</style>

A few moments from the lab and from the road.

## Group pictures

<div class="row mt-3 gallery-hero">
    <div class="col-12">
        {% include figure.html path="assets/img/gallery/Jozsef_group.JPG" class="img-fluid z-depth-1" zoomable=true alt="Research group with Jozsef Kovecses" caption="With Jozsef Kovecses" %}
    </div>
</div>

## Conference

### NeurIPS

<div class="row mt-2 gallery-row-equal">
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/gallery/NEURIPS_present.jpg" class="img-fluid z-depth-1" zoomable=true alt="Presenting at NeurIPS" caption="Presenting at NeurIPS" %}
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/gallery/NEURIPS_myosuite.PNG" class="img-fluid z-depth-1" zoomable=true alt="MyoSuite at NeurIPS" caption="MyoSuite at NeurIPS" %}
    </div>
</div>

### ICORR

<div class="row mt-2 gallery-row-equal">
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/gallery/ICORR_group.JPG" class="img-fluid z-depth-1" zoomable=true alt="Group at ICORR" caption="Group at ICORR" %}
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/gallery/ICORR_present.JPG" class="img-fluid z-depth-1" zoomable=true alt="Presenting at ICORR" caption="Presenting at ICORR" %}
    </div>
</div>

## Summer school

<div class="row mt-3 gallery-summer">
    <div class="col-12 col-lg-10 mx-auto">
        {% include figure.html path="assets/img/gallery/UBC_group.jpg" class="img-fluid z-depth-1" zoomable=true alt="Summer school at UBC" caption="Summer school at UBC" %}
    </div>
</div>

## Internships

<div class="row mt-3 gallery-row-equal">
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/gallery/NEURIPS_group.JPG" class="img-fluid z-depth-1" zoomable=true alt="Internship at EPFL" caption="EPFL" %}
    </div>
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/gallery/NRC_intern.JPG" class="img-fluid z-depth-1" zoomable=true alt="Internship at the NRC" caption="National Research Council Canada" %}
    </div>
</div>
