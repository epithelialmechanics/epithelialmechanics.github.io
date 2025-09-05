---
layout: default
title:  Delegates
description: Thread contributing members of the Epithelial Mechanics Fan club
permalink: /delegates/
images1:
  - {path: /assets/people/NimeshC.png, caption: "Founder & Convenor ", description: "Nimesh Chahare \n Columbia University \n New York, USA"}
  - {path: /assets/people/JuliaE.png, caption: "Co-organizer",  description: "Julia Eckert \n University of Queensland \n Brisbane, Australia"}
images2:    
  - {path: /assets/people/EpiMech2.png, description: "Julia Eckert \n University of Queensland \n Brisbane, Australia"}
---

<div class="gallery1">
  {% for image in page.images1 %}
    <div class="gallery-item">
      <a href="{{ site.baseurl }}{{ image.path }}">
        <img src="{{ site.baseurl }}{{ image.path }}"/>
      </a>
      <div class="image-caption">{{ image.caption }}</div>
      <div class="image-description">{{ image.description | newline_to_br }}</div>
    </div>
  {% endfor %}
</div>

<div class="gallery2">
  {% for image in page.images2 %}
    <div class="gallery-item">
      <a href="{{ site.baseurl }}{{ image.path }}">
        <img src="{{ site.baseurl }}{{ image.path }}"/>
      </a>
      <div class="image-description">{{ image.description | newline_to_br }}</div>
    </div>
  {% endfor %}
</div>


<style>
  .gallery1 {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    max-width: 800px;
    margin: 0 auto;
  }

  .gallery2 {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 800px;
    margin: 0 auto;
  }
  
  .gallery-item {
    overflow: hidden;
    text-align: center;
  }
  
  .gallery-item img {
    width: 100%;
    height: auto;
    aspect-ratio: 1/1;
    object-fit: cover;
    transition: transform 0.5s ease-in-out;
  }
  
  .gallery-item:hover img {
    transform: scale(1.1);
  }
  
  .image-caption {
    margin-top: 10px;
    font-size: 0.9em;
    color: #666;
  }
</style>





<!--
<div class="gallery">
  {% for image in page.images %}
    <div class="gallery-item">
      <a href="{{ site.baseurl }}{{ image.path }}">
        <img src="{{ site.baseurl }}{{ image.path }}"/>
      </a>
      <div class="image-caption">{{ image.caption }}</div>
      <div class="image-description">{{ image.description | newline_to_br }}</div>
    </div>
  {% endfor %}
</div>

<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    max-width: 800px;
    margin: 0 auto;
  }
  
  .gallery-item {
    overflow: hidden;
    text-align: center;
  }
  
  .gallery-item img {
    width: 100%;
    height: auto;
    aspect-ratio: 1/1;
    object-fit: cover;
    transition: transform 0.5s ease-in-out;
  }
  
  .gallery-item:hover img {
    transform: scale(1.1);
  }
  
  .image-caption {
    margin-top: 10px;
    font-size: 0.9em;
    color: #666;
  }
</style>
-->
