---
layout: page
title: Galerías
permalink: /gallery/
images: 
  - image_path: https://cduranalarcon.github.io/images/01.jpg
    title: Apple Pie
  - image_path: https://cduranalarcon.github.io/images/02.jpg
    title: Birthday Cake
  - image_path: https://cduranalarcon.github.io/images/03.jpg
    title: Black Forest
  - image_path: https://cduranalarcon.github.io/images/04.jpg
    title: Brownie
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="images/{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
