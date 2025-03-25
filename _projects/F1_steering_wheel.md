---
layout: post
title: AMG F1 Steering Wheel
date: 2024-10-10 00:00:00
description: A detailed guide to designing, 3D printing, and assembling a replica Formula 1 steering wheel.
img: assets/img/f1wheel.jpg
importance: 3
category: 3d-printing
giscus_comments: true
---

## 3D Printed F1 Steering Wheel Replica

In this project, I designed and 3D printed a replica of a Formula 1 steering wheel. The goal was to create an accurate and functional replica, complete with buttons and dials, suitable for use in a racing simulator setup.

The process involved 3D modeling, 3D printing, post-processing (sanding, painting), and assembly of the parts, as well as adding functional electronics for the buttons. Additionally I created a custom PCB to distribute the controls and simplify the wiring. 

### Design Process and 3D Modeling 

The first step was creating a 3D model of the F1 steering wheel. I used Fusion 360 to model the details, ensuring the layout and dimensions matched real F1 wheels as closely as possible by following reference images of the W11 wheel. This is by far the most complex CAD project I have undertaken, and matching features using only reference images was challenging.

<div class="container mt-3">
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/cad1.png" title="3D Modeling of Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/cad2.png" title="Slicing the 3D Model for Printing" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/cad3.png" title="3D Printing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/cad4.png" title="Finishing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>

<div class="caption">
    Left Top: The exploded view 3D model of the F1 steering wheel. Right Top: CAD model coloured by part, front view. Left Bottom: CAD in 3D rendering software. Right Bottom:  CAD model coloured by part, back view.
</div>

### 3D Printing and Assembly

Once the design was ready, I printed the parts using a ABS plastic to ensure the strength and durability of the wheel. The print was split into multiple parts for easier printing and post-processing. ABS can be sanded and painted to a reasonably high quality surface finish. After printing, I glued the sections together, sanded and painted the parts to give them a smooth, professional finish.

<div class="container mt-3">
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/printed_half.jpg" title="3D Modeling of Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/sanded_rear.jpg" title="Slicing the 3D Model for Printing" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/paint1.jpg" title="3D Printing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/paint2.jpg" title="Finishing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>

<div class="caption">
    Left: Assembly of the 3D printed parts. Right: Sanding and painting to give the steering wheel a high-quality finish.
</div>

### Custom PCB Distribution Board

Due to the high number of controls on the wheel the wiring would be extremely complex, especially as I require a button matrix of diodes to consolidate the number of buttons into a manageable quantity for an Arduino Nano to process. To resolve this issue I decided to design a custom PCB wiring breakout board. This was the first time exploring PCB design and was a steep learning curve. Using video tutorials I was able to design my own custom board that fit my requirements. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/f1_wheel_pcb.jpg" title="Wiring Electronics into the Wheel" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/f1_wheel_pcb2.jpg" title="Completed 3D Printed F1 Steering Wheel" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: Electrical design schematic. Right: The final PCB delivered by JLC PCB service. 
</div>

### Electronics and Finishing Touches

For the buttons and dials, I used basic electronics to create a functional steering wheel for use in a racing simulator. I wired the buttons to an Arduino controller, enabling them to act as inputs for racing games.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/f1_wheel_electronics.jpg" title="Wiring Electronics into the Wheel" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/f1_wheel_electronics2.jpg" title="Completed 3D Printed F1 Steering Wheel" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Above: Wiring the buttons and dials to a controller.
</div>

### Button Detailing

The text on the buttons was created using water transfer film. The buttons were prepainted and then the printed text transferred to the surface. It was finally sealed in using a matt laquer coat. 

<div class="container mt-3">
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/button1.jpg" title="3D Modeling of Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/button2.jpg" title="Slicing the 3D Model for Printing" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/button3.jpg" title="3D Printing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/button4.jpg" title="Finishing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>

<div class="caption">
    Button detailing
</div>

### Final Thoughts

Creating this 3D printed replica F1 steering wheel was a challenging yet rewarding project. The attention to detail in modeling, combined with precision in 3D printing, resulted in a highly realistic and functional wheel for racing simulators.

---

#### Key Features of this Project:

- **Software Used**: Fusion 360
- **Filament**: ABS filament
- **Functional Features**: Integrated buttons and dials with Arduino support to sync to PC as Joystick.
- **Applications**: Ideal for sim racing setups or as a display model.

---
