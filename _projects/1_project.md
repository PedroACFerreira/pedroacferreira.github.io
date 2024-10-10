---
layout: page
title: Research
description: Images for research and review articles
img: assets/img/5.jpg
importance: 1
category: Portfolio
related_publications: false
---

These are images developed for different publications, either research of review articles. 

<div class="row">
    <div class="col-xl mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="Cerebellar microglia development" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
    Cerebellar microglia development. 
</div>

<div class="row justify-content-sm-center">
    <div class="col-lg mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-lg mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left - Cerebellar circuit - included in my PhD thesis
    Right - Microgli aging - included in "The old guard: Age-related changes in microglia and their consequences" @ doi: 10.1016/j.mad.2021.111512
</div>

 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2.png" title="Microglia Functions" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Microglia functions - Included in review article "Microglia‐dependent remodeling of neuronal circuits" @ doi: 10.1111/jnc.15689
</div>

<div class="row">
    <div class="col-xl mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Microglia GIF.gif" title="Microglia Gif" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
    3D Reconstruction of a microglia cell that engulfed neuronal material
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

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
