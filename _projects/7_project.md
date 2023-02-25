---
layout: page
title: 3D reconstruction from Multi-view images
description: Register the 3D reconstructed views through ICP(Iterative Closest Point). (Computer Vision, Multi-view, 3D registration, ICP)
img: assets/img/multiview.png
importance: 5
category: work
---

3D mesh of the object is constructed through 3D registration of multiple 2.5D depth maps. Such maps are generated through multi-view reconstruction using feature matching.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/multiview.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Multi-view 3D reconstruction.
</div>

Multiple views are collected through the capture system from various angles around the object.
