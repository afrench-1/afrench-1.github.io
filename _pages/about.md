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


As a dedicated Manufacturing Engineer with a BEng (Bachelor of Engineering) from the Univeristy of Warwick, I specialise in process optimization and innovative manufacturing solutions within the automotive sector. With hands-on experience from multiple vehicle launches, and implementing lean manufacturing principles, I have successfully contributed to various projects that enhance productivity and quality in production environments. I am working towards certification in Lean Six Sigma Green Belt, and I am a member of the IET, continually seeking opportunities for professional growth and skill development in the dynamic field of manufacturing.

<head>
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
    }

    body {
      background: #eee;
      font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
      font-size: 14px;
      color: #000;
      margin: 0;
      padding: 0;
    }

    .swiper {
      width: 100%;
      padding-top: 50px;
      padding-bottom: 50px;
    }

    .swiper-slide {
      background-position: center;
      background-size: cover;
      width: 300px;
      height: 300px;
    }

    .swiper-slide img {
      display: block;
      width: 100%;
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
    <div class="swiper-slide"><img src="assets/img/9.jpg" alt="Slide 1"/></div>
    <div class="swiper-slide"><img src="assets/img/8.jpg" alt="Slide 2"/></div>
    <div class="swiper-slide"><img src="assets/img/9.jpg" alt="Slide 3"/></div>
    <div class="swiper-slide"><img src="assets/img/10.jpg" alt="Slide 4"/></div>
    <div class="swiper-slide"><img src="assets/img/12.jpg" alt="Slide 5"/></div>
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