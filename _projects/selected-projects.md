---
layout: page
title: Selected Projects
description: A short selection of notable projects (6DOF arm, Flight simulator, and others).
img: assets/img/6DOF_2020.jpg
importance: 3
category: work
related_publications: false
_styles: |
  .project-thumb { max-height: 220px; width: auto; display:block; margin-left:auto; margin-right:auto; }
  .embed-responsive {
    position: relative;
    display: block;
    width: 100%;
    padding: 0;
    overflow: hidden;
  }
  .embed-responsive::before {
    content: "";
    display: block;
    padding-top: 56.25%; /* 16:9 */
  }
  .embed-responsive .embed-responsive-item,
  .embed-responsive iframe,
  .embed-responsive video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }
---

This page highlights a few notable projects chosen for impact and demonstration value.

YouTube demo:

<div class="embed-responsive embed-responsive-16by9 mt-3 mb-3">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/DDDcM8rqQtk" allowfullscreen></iframe>
</div>

<div class="text-justify" markdown="1">
This page highlights a few notable projects chosen for impact and demonstration value. Below are brief descriptions and representative images for each showcased system.
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6DOF_2020.jpg" title="6DOF Robotic Arm" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/Flight_sim_2019.png" title="Flight Simulator" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/SCARA_2022.jpg" title="SCARA" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/figura3.png" title="Project image 4" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/figura8.png" title="Project image 5" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/farmbot_2022.jpg" title="Application: agricultural robot" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
</div>

<div class="text-justify" markdown="1">
Short notes:

- **6DOF Arm:** Kinematics and control experiments demonstrating precision manipulation and trajectory planning.
- **Flight simulator:** Full‑stack simulator used for UAV algorithm validation and operator training.
- **SCARA:** Collaborative robot application for continuous classification of products.

More details (code, images, videos) can be added per project on request.
</div>
