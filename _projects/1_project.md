---
layout: page
title: Deep Prefetching Interactive Volume Renderer
description: GPU-accelerated multi-resolution volume visualization for large-scale data using deep prefetching neural network, RmdnCache.
img: assets/img/renderer.png
importance: 1
category: work
---

RmdnCache Renderer is a GPU-accelerated multi-resolution volume visualization renderer on large-scale volumetric dataset. It utilized the optimized pre-trained RmdnCache neural network for microblock prediction and achieve an effective and efficient prefetching with minimal latency. This can be generalized to various volume visualizations for best responsiveness for interactive large-scale volume visualiztion.

CUDA is used for multi-core parallelism of rendering on GPU. LibTorch is used to inference the pre-trained RmdnCache network on CPU. Detail implementation can be accessed from my GitHub repo [here](https://github.com/sunjianxin/Deep-prefetching-renderer).

The demo below shows the prefetching performance, interm of number of missing microblocks in red color, across popular prefetching algorithms and the RmdnCache pre-trained network using the interactive volume render. Our renderer can achieve responsive interactive volume visualization on large-scale Flame volume dataset of 7GB in size.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/renderer.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Global view of microblocks and volume, and the camera view of the final rendering.
</div>

<iframe width="960" height="480" src="https://www.youtube.com/embed/SBPq6zV1LUQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<div class="caption">
    Volume rendering in real time on large-scale dataset showing performance comparison.
</div>

Dataset:
Flame dataset
Size:
7GB
