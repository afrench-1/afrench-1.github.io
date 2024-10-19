---
layout: post
title: BLDC 50A Driver
date: 2024-10-10 00:00:00
description: A Field-oriented-control brushless DC motor controller. <br /> <i class="fa-solid fa-calendar fa-sm"></i> 2024 
img: assets/img/BLDC3dview.jpg
importance: 3
category: electronics
giscus_comments: true
---
> [!NOTE]   
> **Disclaimer** this drive design was created by Thomas Godden, check out his <a href="https://github.com/LegoYoda112/BLDC_Driver">github</a>.

## PCB Electronics Project Overview

In this project, I designed and developed a custom printed circuit board (PCB) for a [specific function like power management, signal processing, etc.]. The aim was to create a high-performance, compact, and reliable PCB for use in various electronic applications.

The project involved schematic design, component selection, PCB layout, prototyping, and testing. Below are the highlights of the process with images showcasing each step.

### Design Process

I started with the schematic design using software such as KiCad, Altium, or Eagle. Component selection was critical to ensure the best performance while minimizing space and cost. After finalizing the design, I laid out the PCB tracks and performed design rule checks to make sure there were no errors before manufacturing.

### Images of PCB Design & Development

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

### Testing and Results

After assembling the PCB, I conducted several tests to ensure the board was functioning correctly. I used [testing methods, e.g., multimeter for continuity tests, oscilloscope for signal integrity, etc.].

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pcb_testing.jpg" title="PCB Testing with Multimeter" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pcb_oscilloscope.jpg" title="Oscilloscope Measuring Signals" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: Continuity testing with a multimeter. Right: Signal integrity measured using an oscilloscope.
</div>

### Final Thoughts

This project provided valuable insights into PCB design and electronics engineering. From schematic design to prototype testing, it reinforced the importance of careful planning and thorough testing.

---

#### Key Features of this Project:

- **Software Used**: [KiCad/Altium/Eagle]
- **PCB Layers**: [2-layer/4-layer]
- **Applications**: [E.g., Power supply design, microcontroller board, signal processing]
- **Challenges**: [Any challenges faced, e.g., thermal management, signal noise, etc.]

Feel free to explore the images, code, and more details in the repository.

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

The design files and firmware for this PCB are available on [GitHub link] or another repository platform for download.

{% raw %}
```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/pcb_final.jpg" title="Final Assembled PCB" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/pcb_closeup.jpg" title="Close-up of PCB" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
