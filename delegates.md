---
layout: default
title:  Delegates
description: Thread contributing members of the Epithelial Mechanics Fan club
permalink: /delegates/
images1:
  - {path: /assets/people/NimeshC.png, caption: "Founder & Convenor ", name: "Nimesh Chahare", description: "Columbia University \n New York, USA"}
  - {path: /assets/people/JuliaE.png, caption: "Co-organizer", name: "Julia Eckert",  description: "University of Queensland \n Brisbane, Australia"}
images2: 
  - {path: /assets/people/EpiMechFC.png, name: "Abdel Rahman Abdel Fattah", affiliation: "...", origin: "Vienna, Austria"}
  - {path: /assets/people/EpiMechFC.png, name: "Akshar Rao", affiliation: "...", origin: "Bengaluru, India"}
  - {path: /assets/people/EpiMechFC.png, name: "Andreas Schönit", affiliation: "...", origin: "Paris, France"}
  - {path: /assets/people/EpiMechFC.png, name: "Arthur Michaut", affiliation: "...", origin: "Paris, France"}
  - {path: /assets/people/EpiMechFC.png, name: "Augusto Borges", affiliation: "...", origin: "Munich, Germany"}
  - {path: /assets/people/EpiMechFC.png, name: "Benjamin Swedlund", affiliation: "...", origin: "Los Angeles, USA"}
  - {path: /assets/people/EpiMechFC.png, name: "Clément Hallopeau", affiliation: "...", origin: "Barcelona, Spain"}
  - {path: /assets/people/EpiMechFC.png, name: "David Brückner", affiliation: "...", origin: "Vienna, Austria"}
  - {path: /assets/people/EpiMechFC.png, name: "Dhiraj Indana", affiliation: "...", origin: "Pasadena, USA"}
  - {path: /assets/people/EpiMechFC.png, name: "Eirini Maniou", affiliation: "...", origin: "Padova, Italy"}
  - {path: /assets/people/EpiMechFC.png, name: "Eleni Papafilippou", affiliation: "...", origin: "London, UK"}
  - {path: /assets/people/EpiMechFC.png, name: "Emma Lång", affiliation: "...", origin: "Oslo, Norway"}
  - {path: /assets/people/EpiMechFC.png, name: "Feyza Nur Arslan", affiliation: "...", origin: "Lausanne, Switzerland"}
  - {path: /assets/people/EpiMechFC.png, name: "Guillermo Martínez Ara", affiliation: "...", origin: "Barcelona, Spain"}
  - {path: /assets/people/EpiMechFC.png, name: "Ibrahim Erbhay", affiliation: "...", origin: "Barcelona, Spain"}
  - {path: /assets/people/EpiMechFC.png, name: "Isabela Fortunato", affiliation: "...", origin: "Barcelona, Spain"}
  - {path: /assets/people/EpiMechFC.png, name: "Jianxiong Wang", affiliation: "...", origin: "Brisbane, Australia"}
  - {path: /assets/people/EpiMechFC.png, name: "Kate Cavanaugh", affiliation: "...", origin: "San Francisco, USA"}
  - {path: /assets/people/EpiMechFC.png, name: "Lara Hundsdorfer", affiliation: "...", origin: "Tübingen, Germany"}
  - {path: /assets/people/EpiMechFC.png, name: "Leone Rossetti", affiliation: "...", origin: "London, UK"}
  - {path: /assets/people/EpiMechFC.png, name: "Lucas Anger", affiliation: "...", origin: "Paris, France"}
  - {path: /assets/people/EpiMechFC.png, name: "Lucia Baldauf", affiliation: "...", origin: "London, UK"}
  - {path: /assets/people/EpiMechFC.png, name: "Maik Bischoff", affiliation: "...", origin: "Chapel Hill, USA"}
  - {path: /assets/people/EpiMechFC.png, name: "Makis Ampartzidis", affiliation: "...", origin: "Cambridge, UK"}
  - {path: /assets/people/EpiMechFC.png, name: "Mathieu Dedenon", affiliation: "...", origin: "Geneva, Switzerland"}
  - {path: /assets/people/EpiMechFC.png, name: "Miquel Bosch", affiliation: "...", origin: "Barcelona, Spain"}
  - {path: /assets/people/EpiMechFC.png, name: "Neha Ghosh", affiliation: "...", origin: "New York, USA"}
  - {path: /assets/people/EpiMechFC.png, name: "Rajendra Singh Negi", affiliation: "...", origin: "Syracuse, USA"}
  - {path: /assets/people/EpiMechFC.png, name: "Sayuki Hirano", affiliation: "...", origin: "Kyoto, Japan"}
  - {path: /assets/people/EpiMechFC.png, name: "Tom Golde", affiliation: "...", origin: "Barcelona, Spain"}
  - {path: /assets/people/EpiMechFC.png, name: "Valeria Venturini", affiliation: "...", origin: "Barcelona, Spain"}
  - {path: /assets/people/EpiMechFC.png, name: "Vina Putra", affiliation: "...", origin: "Sydney, Australia"}
  - {path: /assets/people/EpiMechFC.png, name: "Weiyi Qian", affiliation: "...", origin: "New York, USA"}
  - {path: /assets/people/EpiMechFC.png, name: "Yamini Ravichandran", affiliation: "...", origin: "Geneva, Switzerland"}
  - {path: /assets/people/EpiMechFC.png, name: "Zoya Mann", affiliation: "...", origin: "Brisbane, Australia"}
---

<div class="gallery1">
  {% for image in page.images1 %}
    <div class="gallery-item">
      <a href="{{ site.baseurl }}{{ image.path }}">
        <img src="{{ site.baseurl }}{{ image.path }}"/>
      </a>
      <div class="image-caption">{{ image.caption }}</div>
      <div class="image-description"><b>{{ image.name | newline_to_br }}</b></div>
      <div class="image-description">{{ image.description | newline_to_br }}</div>
    </div>
  {% endfor %}
</div>

<br>
<div class="gallery2">
  {% for image in page.images2 %}
    <div class="gallery-item">
<!--      
      <a href="{{ site.baseurl }}{{ image.path }}">
        <img src="{{ site.baseurl }}{{ image.path }}"/>
      </a>
-->      
      <div class="image-description"><b>{{ image.name | newline_to_br }}</b></div>
 <!--      
      <div class="image-description">{{ image.affiliation | newline_to_br }}</div>
 -->      
      <div class="image-description">{{ image.origin | newline_to_br }}</div>
    </div>
  {% endfor %}
  <br>
</div>

<br>
<div style="text-align: center;">
  <a href="{{ site.baseurl }}/assets/people/DelegatesMap.png">  
            <img src="{{ site.baseurl }} /assets/people/DelegatesMap.png"/>
  </a>
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
