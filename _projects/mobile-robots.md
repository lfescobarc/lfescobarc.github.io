---
layout: page
title: Cyber-Physical Systems
description: Mobile Robots & IoT Architectures.
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

<div class="text-justify" markdown="1">
This video details the engineering and deployment of an Omnidirectional Automated Guided Vehicle (AGV), developed to optimize logistics for a manufacturing company in Ecuador. As part of a multi-disciplinary team, I applied the Cyber-Physical System (CPS) frameworks from my research to architect a robust, industrial-grade platform. The final system features a custom holonomic drive with precise kinematic control, successfully validating advanced academic theories against the rigorous reliability requirements of a real-world production environment.
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/figura3.png" title="Multi‑robot testbed" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/figura8.png" title="Experimental setup" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/multi_robot_2020.png" title="Educational multi-robot platform" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
</div>

<div class="text-justify" markdown="1">
This research focuses on the design and implementation of autonomous mobile robot platforms conceived as CPS. Moving beyond traditional standalone robotics, these platforms are engineered to serve as accessible, low-cost educational and research tools that seamlessly integrate physical hardware with digital computation. The mechanical design emphasizes omnidirectional mobility and modularity, developed using advanced mechatronic methodologies (such as the V-Model) to ensure they can be easily replicated and adapted for complex academic experiments in control theory and automation.
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/multi_robot_2022.png" title="Multi-robot collaborative work" class="img-fluid rounded z-depth-1 mx-auto d-block project-thumb" %}
  </div>
</div>

<div class="text-justify" markdown="1">
A core innovation of this work is the deployment of a robust Internet of Things (IoT) architecture to manage multi-robot teams. By utilizing the MQTT protocol as a communication backbone, the system enables centralized monitoring and decentralized decision-making from the cloud, allowing multiple robots to collaborate on shared tasks like object classification and sorting. The navigation stack integrates trajectory planning algorithms with this IoT framework, ensuring that the fleet can coordinate movements, avoid collisions, and execute collaborative missions efficiently even under network constraints. ({% cite guerra2022multirobot %}, {% cite escobar2020andescon %}, {% cite gonzalez2018iot %}, {% cite toapanta2020autonomous %}).
</div>
