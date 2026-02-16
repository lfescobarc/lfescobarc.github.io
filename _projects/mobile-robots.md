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

Related publications are listed on the Publications page; select papers demonstrate the algorithms used and the datasets collected.
