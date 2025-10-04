---
layout: page
title: Animal physiology and behavior
description: Physical limits in avian respiration.
img: assets/img/12.jpg
importance: 1
category: Physics of Life
related_publications: true
---
Many physiological functions, and all animal behaviors, emerge from the interaction between the nervous system, the body, and the environment. Studying this interaction is a key opportunity to address what I consider two of the deepest questions in science: how the brain functions and how these processes are framed in evolutionary history. The main reasons are that peripheral structures decode neural signals into movement, and that the parameters of the body and the nervous system have been shaped by evolution.

During my PhD, under the advice of Prof. Gabriel B. Mindlin, I investigated avian respiration. Birds unceasingly expand and contract a set of air sacs to ventilate rigid lungs. Beyond sustaining life, the respiratory frequency sets the rhythm of song, which is usually composed of very rapid vocalizations. Thus, respiration provided us a framework to investigate fundamental aspects in physiology and behavior, including (i) the extent to which these are constrained by physics and physical properties of the body, and (ii) the degree of synergy between the nervous system and the biomechanics.

Figure 1 – pressure decoding

Combining physiological recordings with a nonlinear model, we found that birds breathe and sing at resonances of their respiratory biomechanics{% cite fainstein2021birds %}{% cite fainstein2025birds %}. These resonances enable an efficient translation of motor instructions into the air-pressure responsible for lung ventilation. Our results reveal an intimate relationship between the dynamics of neural motor circuits and the physical properties of the body and the environment, and show that optimization strategies can be shared across behavioral states. Additionally, this work informs on the interpretable decoding of neural signals into physiological variables, a key step for successful neural-interface technologies.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
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
