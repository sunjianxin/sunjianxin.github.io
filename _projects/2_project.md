---
layout: page
title: Prefetching Neural Network
description: Prefetching neural network, RmdnCache, is a predictive model for microblock prediction using RNN + MDN. (RNN, MDN, Deep Learning, Large-scale Data Visualization, Ray Casting, CUDA, Pytorch)
img: assets/img/network.png
importance: 2
category: work
---

Prefetching neural network, RmdnCache, is a predictive model for multi-resolution microblock prefetching using RNN + MDN. The effectiveness an efficiency of such prefiction can greatly reduce the input latency of a typical interactive volume visualization on large-scale dataset. 

The network is trained on our collected training dataset capturing the explorating pattern of general user for volume analytics tasks. RNN and MDN are trained respectively on two different domains, Cartiesian domain and Spherical domain, in a transfer learning fashion. Network is trained using Pytorch through CUDA on GPU.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/teaser.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Demostration of predicted POV and its range for calculating prefetching microblocks.
</div>

Using RmdnCache gives the lowest microblock cache miss rate and input latency comparing to other prefetching algorithms.
