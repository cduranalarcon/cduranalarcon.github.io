---
layout: page
title: Galerías
permalink: /gallery/
images: 
  - image_path: 01.jpg
    title: Apple Pie
  - image_path: 02.jpg
    title: Birthday Cake
  - image_path: 03.jpg
    title: Black Forest
  - image_path: 04.jpg
    title: Brownie
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>


<div class="gallery-wrapper">
  <div class="gallery">
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 active transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
      <div class="item-wrapper">
        <figure class="gallery-item image-holder r-3-2 transition"></figure>
      </div>
  </div>
</div>
