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

The process involved 3D modeling, 3D printing, post-processing (sanding, painting), and assembly of the parts, as well as adding functional electronics for the buttons.

### Design Process

The first step was creating a 3D model of the F1 steering wheel. I used Fusion 360 to model the details, ensuring the layout and dimensions matched real F1 wheels as closely as possible by following reference images of the W11 wheel. Once the model was finalized, I sliced it for 3D printing.

### 3D Modeling & Slicing

<div class="container mt-3">
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/f1_wheel_modeling.jpg" title="3D Modeling of Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/f1_wheel_slicing.jpg" title="Slicing the 3D Model for Printing" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="row">
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/f1_wheel_printing.jpg" title="3D Printing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-md-6 mb-3">
            {% include figure.liquid loading="eager" path="assets/img/f1_wheel_finishing.jpg" title="Finishing the Steering Wheel" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>

<div class="caption">
    Left: The 3D model of the F1 steering wheel. Middle: The model sliced and prepared for printing. Right: The printing process in action.
</div>

### 3D Printing and Assembly

Once the design was ready, I printed the parts using a [PLA/ABS/Carbon-fiber filament] to ensure the strength and durability of the wheel. The print was split into multiple parts for easier printing and post-processing.

After printing, I sanded and painted the parts to give them a smooth, professional finish. Assembly followed, where I glued the components together, added the buttons and dials, and integrated basic electronics.

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

### Electronics and Finishing Touches

For the buttons and dials, I used basic electronics to create a functional steering wheel for use in a racing simulator. I wired the buttons to an Arduino controller, enabling them to act as inputs for racing games.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/f1_wheel_electronics.jpg" title="Wiring Electronics into the Wheel" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/f1_wheel_final.jpg" title="Completed 3D Printed F1 Steering Wheel" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: Wiring the buttons and dials to a controller. Right: The final assembled F1 steering wheel ready for simulation racing.
</div>

### Final Thoughts

Creating this 3D printed replica F1 steering wheel was a challenging yet rewarding project. The attention to detail in modeling, combined with precision in 3D printing, resulted in a highly realistic and functional wheel for racing simulators.

---

#### Key Features of this Project:

- **Software Used**: [Fusion 360]
- **Filament**: [PLA/ABS/Carbon-fiber]
- **Functional Features**: Integrated buttons and dials with Arduino support.
- **Applications**: Ideal for sim racing setups or as a display model for F1 enthusiasts.

Feel free to explore the images and project files below. The 3D models and assembly instructions can be found in the repository.

---

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/f1_wheel_display.jpg" title="Final 3D Printed Steering Wheel on Display" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/f1_wheel_detail.jpg" title="Close-up of Buttons and Dials" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: The final 3D printed F1 steering wheel on display. Right: A close-up of the functional buttons and dials.
</div>
