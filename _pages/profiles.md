---
layout: page
permalink: /people/
nav: true
nav_order: 7
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---
<h2>Current PhDs </h2>

* **Emile Gros** (Octobre 2023-onwards)
  *  <a href="https://theses.fr/s377820"> Recherche multidisciplinaire pour la caractérisation du fonctionnement hydrogéologique des aquifères volcaniques de la Martinique : édifice volcanique du Morne Jacob. </a>  
  *  Collaboration with Sophie Violette (ENS) and  <a href="https://mq.linkedin.com/in/benoit-vittecoq-brgm-martinique"> Benoit Vittecoq </a> (BRGM)   </li>  
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

<ul>
<li> <h5> Emile Gros (Octobre 2023-onwards) </h5> 
     <a href="https://theses.fr/s377820"> Recherche multidisciplinaire pour la caractérisation du fonctionnement hydrogéologique des aquifères volcaniques de la Martinique : édifice volcanique du Morne Jacob. </a>  
    Collaboration with Sophie Violette (ENS) and  <a href="https://mq.linkedin.com/in/benoit-vittecoq-brgm-martinique"> Benoit Vittecoq </a> (BRGM)   </li>  
<li> <h5> Julien Doucot (Octobre 2022-onwards) </h5>  <a href="https://theses.fr/s348406"> La diagenèse précoce des sédiments carbonatés au laboratoire : approche expérimentale des processus géologiques et leur rôle sur les propriétés réservoirs. </a> Collaboration with Jean Baptiste Regnet and Philippe Robion <a href="https://gec.cyu.fr/"> CYU </a>  </li>
    
<li> <h5> Théo Briolet (Decembre 2021-onwards) </h5> <a href="https://theses.fr/s298987"> Etude expérimentale intégrée de l'impact de l'altération des roches sur leurs propriétés hydromécaniques </a> Collaboration with Elisabeth Bemer and Olivier Sissmann from <a href="https://www.ifpenergiesnouvelles.fr/">IFPEN </a>   </li>
  
<ul>





<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
