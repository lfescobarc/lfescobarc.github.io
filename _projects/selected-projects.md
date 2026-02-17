---
layout: page
title: Selected Projects
description: A selection of projects spanning Motion Simulation, Social Robotics, and Industrial Optimization.
img: assets/img/publication_preview/yaniwawa_2020.PNG
importance: 3
category: work
related_publications: true
_styles: |
  .project-thumb { max-height: 200px; width: auto; display:block; margin-left:auto; margin-right:auto; }
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

<div class="text-justify" markdown="1">
This page highlights a few notable projects chosen for their technical impact and demonstration value. These works bridge the gap between theoretical research and practical application, often involving student collaboration and real-world deployment.

### **Motion Simulation & Cyber-Physical Systems**

One of my most extensive projects involved the development of a **Real-Time Flight Simulator** for pilot training. We utilized a modified Stewart-Gough platform to replicate flight dynamics and validated the system through a digital twin {% cite serrano2018spatial %}. The system was designed using **Cyber-Physical Systems (CPS)** methodologies, integrating a spatial disorientation module to simulate hazardous flight conditions safely {% cite villacis2017icpcsi %}.
</div>

<div class="embed-responsive embed-responsive-16by9 mt-3 mb-3">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/DDDcM8rqQtk" allowfullscreen></iframe>
</div>

<div class="text-justify" markdown="1">
This platform demonstrated how kinematic theory could be applied to build robust, low-cost training hardware. We further extended this research to smaller scale simulator {% cite duquecamacho2020stewart %}.

---

### **Social Robotics & Education**

My interest in accessible robotics led to the development of several platforms designed for human-robot interaction. We built  a **6-DOF anthropomorphic robot** to serve as a testbed for teaching kinematics and trajectory planning {% cite galarza2020aim %}. Robots specifically engineered for children's education and human interaction as **NAR** {% cite espinoza2020nar %} and **VISART** {% cite rodriguez2020visart %}.
</div>

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3">
         {% include figure.liquid path="assets/img/publication_preview/yaniwawa_2020.PNG" title="Yaniwawa" class="img-fluid rounded z-depth-1 project-thumb" %}
    </div>
    <div class="col-sm-6 mt-3 text-justify">
        <p>In addition to robotic agents, we explored innovative teaching tools like <strong>YaniWawa</strong>, an augmented reality sandbox that uses programmable models to teach topography and physics concepts interactively {% cite cardenas2020yaniwawa %}. These projects emphasize the role of mechatronics in enhancing educational engagement.</p>
    </div>
</div>

---

### **Industrial Automation & Optimization**

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3">
         {% include figure.liquid path="assets/img/publication_preview/Layout_2022.png" title="Layout_2022" class="img-fluid rounded z-depth-1 project-thumb" %}
    </div>
    <div class="col-sm-6 mt-3 text-justify">
        <p>Beyond robotics hardware, I have applied <strong>Discrete Event Simulation (DES)</strong> and meta-heuristic algorithms to optimize manufacturing processes. Working with small enterprises in Ecuador, we utilized DES software to analyze and select optimal plant layouts, significantly improving process flow and efficiency {% cite izquierdo2021fms %}, {% cite cisneros2022plantlayout %}.</p>
    </div>
</div>
