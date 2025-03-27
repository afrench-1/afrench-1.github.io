---
layout: post
title: BLDC 50A Driver
date: 2024-10-10 00:00:00
description: A Field-oriented-control brushless DC motor controller.
img: assets/img/BLDC3dview.jpg
importance: 3
category: electronics
giscus_comments: true
---
> [!NOTE]   
> **Disclaimer** this drive design was created by Thomas Godden, check out his <a href="https://github.com/LegoYoda112/BLDC_Driver">github</a>.

## PCB Electronics Project Overview

In this project, I modified and produced a custom printed circuit board (PCB) for a Brushless Motor controller running Field Oriented Control (FOC). The aim was to create a high-performance, compact, and reliable controller for use in various robotics appliations. 

The project involved schematic design, component selection, PCB layout, prototyping, and testing. Below are the highlights of the process with images showcasing each step.

### Design Process

I started with the schematic design using PCB design software EasyEDA Pro. Component selection was critical to ensure the best performance while minimizing space and cost, the design of the PCB currently being developed by the extremely talented Thomas Godden used components that I would be unable to source. To counter this I modified the design to use lower cost and easily sourced MOSFETs. After finalizing the design,I performed design rule checks to make sure there were no errors before manufacturing that I might have created with my modifications. For fun I also added some designs to the PCB silkscreen. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pcb_schematic.jpg" title="PCB Schematic Design" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pcb_layout.jpg" title="PCB Layout in CAD" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/BLDC3dview.jpg" title="Assembled PCB Prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    On the left: The schematic design. In the middle: The PCB layout in CAD software. On the right: The assembled PCB prototype ready for testing.
</div>

### Ordering PCBs from PCB Manufacturer 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/JLCPCB0.jpg" title="PCB Order" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/JLCPCB.jpg" title="PCB Order" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    On the left: The schematic design. In the middle: The PCB layout in CAD software. On the right: The assembled PCB prototype ready for testing.
</div>

### Final Thoughts

This project provided a huge amount of learning about PCB design and electronics engineering. 

---

#### Key Features of this Project:

- **Software Used**: JLC PCB offer a webbased PCB design tool EASYEDA, it performs similar to autodesk eagle and integrates well into the PCB ordering process from JLCPCB. 
- **PCB Layers**: 2-layer board
- **Applications**: Brushless motor controller utilising Field Oriented Control
- **Challenges**: Software flashing was challenging, this is likely due to using a non-genuine ST-Link and protections are casuing failiures during the flashing process. 

---

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/pcb_final.jpg" title="Final Assembled PCB" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/pcb_closeup.jpg" title="Close-up of PCB" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: Final assembled PCB in the enclosure. Right: Close-up view of the traces and components on the PCB.
</div>

## Leave Your Feedback

Please share your feedback or ask questions using the comments section below!

---

### Code and Schematics

The design files and firmware for this PCB are available on Thomas Goddens <a href="https://github.com/LegoYoda112/BLDC_Driver">github</a> for download.

{% endraw %}
