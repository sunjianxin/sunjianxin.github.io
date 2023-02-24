---
layout: page
title: Interactive Volume Renderer
description: GPU-accelerated multi-resolution volume visualization for large-scale data using deep prefetching neural network, RmdnCache.
img: assets/img/renderer.png
importance: 1
category: work
---

RmdnCache Renderer is a GPU-accelerated multi-resolution volume visualization renderer on large-scale volumetric dataset. It utilized the optimized pre-trained RmdnCache neural network for microblock prediction and achieve an effective and efficient prefetching with minimal latency. This can be generalized to various volume visualizations for best responsiveness for interactive large-scale volume visualiztion.

CUDA is used for multi-core parallelism of rendering on GPU. LibTorch is used to inference the pre-trained RmdnCache network on CPU. Detail implementation can be accessed from my GitHub repo [here](https://github.com/sunjianxin/Deep-prefetching-renderer).

The demo below shows the prefetching performance, interm of number of missing microblocks in red color, across popular prefetching algorithms and the RmdnCache pre-trained network using the interactive volume render.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/renderer.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Global view of microblocks and volume, and the camera view of the final rendering.
</div>

<iframe width="560" height="315" src="https://www.youtube.com/embed/SBPq6zV1LUQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
