---
layout: page
title: Mobile Robots
description: Mobile robotics research and selected examples.
img: assets/img/publication_preview/multi_robot_2022.png
importance: 2
category: work
related_publications: true
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

<div class="embed-responsive embed-responsive-16by9 mt-3 mb-3">
  <iframe class="embed-responsive-item" src="https://drive.google.com/file/d/1lPZNuNo0LifAi7NNBZAjzwJ1ojr-ZEPw/preview" allowfullscreen></iframe>
</div>

Brief: A curated selection of my mobile‑robotics work, including navigation algorithms, perception pipelines, and experimental deployments. Highlights include field studies and published papers on multi‑robot coordination.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/multi_robot_2020.png" title="Multi‑robot testbed" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/multi_robot_2022.png" title="Experimental setup" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/farmbot_2022.jpg" title="Application: agricultural robot" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="text-justify" markdown="1">
This project showcases a curated selection of mobile-robotics research and deployments. Work includes design of base robotic platforms, perception pipelines for real-world environments, and coordination strategies for multi-robot teams. The software stack integrates ROS-based components, lightweight IoT messaging for coordination, and experimental datasets collected in field trials.
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/multi_robot_2022.png" title="Multi-robot collaborative work" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/multi_robot_2020.png" title="Educational multi-robot platform" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/farmbot_2022.jpg" title="Application: agricultural robot" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
</div>

<div class="text-justify" markdown="1">
Selected papers and system descriptions: multi-robot coordination and IoT-based architectures are presented in several works, including collaborative trajectory planning and MQTT-based communication layers. These references describe platforms and methods closely related to the architecture used in this project ({% cite guerra2022multirobot %}, {% cite escobar2020andescon %}, {% cite gonzalez2018iot %}, {% cite toapanta2020autonomous %}).
</div>
