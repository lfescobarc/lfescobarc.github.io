---
layout: page
title: UAV Systems
description: Autonomous UAV Systems for Underground Inspection & Mapping.
img: assets/img/version3.png
importance: 1
category: work
related_publications: true
_styles: |
  .project-thumb { max-height: 220px; width: auto; display:block; margin-left:auto; margin-right:auto; }
---

YouTube demo: 

<div class="embed-responsive embed-responsive-16by9 mt-3 mb-3">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/fpPM8RrUx34" allowfullscreen></iframe>
</div>
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/version3.png" title="UAV prototype" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/drone_deploy.jpeg" title="Field test" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/pillar.png" title="Simulated mine merged Point cloud" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
</div>

Funded by the Alpha Foundation, this research addresses the critical challenges of deploying autonomous robots in hazardous, GNSS-denied subterranean environments. To overcome the limitations of darkness, dust, and lack of global positioning, we developed a custom multi-rotor UAV specifically engineered for underground mine inspection. The system features a robust, collision-tolerant design and utilizes LiDAR-Inertial Odometry (LIO), which proved superior to visual methods for maintaining accurate localization in harsh mine conditions. This hardware platform supports a multi-modal mapping workflow, successfully integrating global LiDAR maps with high-resolution RGB-D scans to create detailed 3D reconstructions of mine pillars and corridors.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/UAV_2025.png" title="Energy aware Path planning" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/min_snap.png" title="Coverage planning" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/point_cloud.png" title="Energy method result" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
</div>

Complementing the hardware development, we introduced a novel Energy-Aware Coverage Path Planning (CPP) algorithm to maximize mission efficiency. While traditional planners optimize for distance, our approach incorporates a specific multi-rotor energy model into a Mixed Integer Linear Programming (MILP) framework. This method generates flight paths that minimize battery consumption rather than just travel distance, achieving up to a 20% reduction in energy usage for 3D inspection tasks. Together, these advancements provide a comprehensive solution for safe, autonomous, and enduring robotic operations in complex underground environments.{% cite escobar2025energy %}

