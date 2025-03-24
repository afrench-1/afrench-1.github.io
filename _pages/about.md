---
layout: about
title: about
permalink: /
subtitle: Manufacturing process engineer

profile:
  align: right
  image: afrench.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Stratford-upon-Avon</p>
    <p>Warwickshire</p>
    <p>United Kingdom</p>

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
--- 


<p class="justify-text">
  As a dedicated Manufacturing Engineer with a BEng (Bachelor of Engineering) from the University of Warwick, I specialise in process optimization and innovative manufacturing solutions within the automotive sector. With hands-on experience from multiple vehicle launches, and implementing lean manufacturing principles, I have successfully contributed to various projects that enhance productivity and quality in production environments. I am continually seeking opportunities for professional growth and skill development in the dynamic field of manufacturing.
</p>

<h2 style="text-align: left; margin-top: 20px; margin-bottom: 20px;">
  <a href="/projects/" style="color: inherit">projects</a>
</h2>

<head>

  <h2 style="text-align: left; margin-top: 20px; margin-bottom: 20px;">
  <a href="/projects/" style="color: inherit">projects</a>
  </h2>

  <meta charset="utf-8" />
  <title>Swiper demo</title>
  <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1" />
  <!-- Link Swiper's CSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />

  <!-- Demo styles -->
  <style>
    html,
    body {
      position: relative;
      height: 100%;
      overflow-x: hidden
    }

    body {
      background: #eee;
      font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
      font-size: 14px;
      color: #000;
      margin: 0;
      padding: 0;
    }

    .swiper-container {
      width: 60%; /* Make the container narrower to allow slides to peek */
      max-width: 900px;
      padding-top: 50px;
      padding-bottom: 50px;
      overflow: visible; /* Allow overflow to show part of adjacent slides */
      margin: 0 auto; /* Center the swiper on the page */
    }

    .swiper-slide {
      background-position: center;
      background-size: cover;
      width: 300px;
      height: 300px;
      border-radius: .25px;
    }

    .swiper-slide img {
      display: block;
      width: 100%;
    }

    .swiper-pagination-bullet-active {
      background-color: #007bff; /* Active dot color (blue) */
    }
  </style>
</head>

<!-- Add Swiper CSS -->
<link
  rel="stylesheet"
  href="https://unpkg.com/swiper/swiper-bundle.min.css"
/>

<!-- Swiper -->
<div class="swiper-container">
  <div class="swiper-wrapper">
      <!-- Each image wrapped in a clickable <a> tag with link to a project -->
      <div class="swiper-slide">
        <a href="https://afrench-1.github.io/projects/robot_arm/" target="_blank">
          <img src="assets/img/robotthumb.jpg" alt="F1 Wheel" />
        </a>
      </div>
      <div class="swiper-slide">
        <a href="https://afrench-1.github.io/projects/3d_printer/" target="_blank">
          <img src="assets/img/3dp1.jpg" alt="3d printer" />
        </a>
      </div>
      <div class="swiper-slide">
        <a href="https://afrench-1.github.io/projects/F1_steering_wheel/" target="_blank">
          <img src="assets/img/f1wheel.jpg" alt="Project 3" />
        </a>
      </div>
      <div class="swiper-slide">
        <a href="https://afrench-1.github.io/projects/cycloidal_gearbox/" target="_blank">
          <img src="assets/img/cycloidal_gearbox_bg.jpg" alt="cycloidal_gearbox" />
        </a>
      </div>
      <div class="swiper-slide">
        <a href="https://afrench-1.github.io/projects/BLDC_driver/" target="_blank">
          <img src="assets/img/BLDC3dview.jpg" alt="BLDC driver" />
        </a>
      </div>
    </div>
  <!-- Add Pagination -->
  <div class="swiper-pagination"></div>
</div>

<!-- Add Swiper JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

<!-- Initialize Swiper with Coverflow effect -->
<script>
  var swiper = new Swiper('.swiper-container', {
    effect: 'coverflow',
    grabCursor: true,
    centeredSlides: true,
    slidesPerView: 'auto',
    loop: true,
    initialSlide: 2,
    coverflowEffect: {
      rotate: 50,
      stretch: 0,
      depth: 100,
      modifier: 1,
      slideShadows: true,
    },
    pagination: {
      el: '.swiper-pagination',
    },
  });
</script>
