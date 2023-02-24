---
layout: page
title: Direct rendering from MFA model
description: MFA-DVR is a direct volume rendering on MFA model and implemented on top of VTK visualization library. (Data modeling and Visualization, C/C++)
img: assets/img/mfa1.png
importance: 1
category: work
---

3D volume rendering is widely used to reveal insightful intrinsic patterns of volumetric datasets across many domains.
However, the complex structures and varying scales of datasets make generating a high-quality volume rendering results efficiently
a challenging task. Multivariate functional approximation (MFA) is a new data model that addresses some of the key challenges of
volume visualization. MFA provides high-order evaluation of values and derivatives anywhere in the spatial domain, mitigating the
artifacts caused by the zero- or first-order interpolation commonly implemented in existing volume visualization algorithms. MFA’s
compact representation improves the space complexity for large-scale volumetric data visualization, while its uniform representation of
both structured and unstructured data allows the same ray casting algorithm to be used for a variety of input data types. In this paper,
we present MFA-DVR, the first direct volume rendering pipeline utilizing the MFA model, for both structured and unstructured volumetric
datasets. We demonstrate improved rendering quality using MFA-DVR on both synthetic and real datasets through a comparative study
with raw and compressed data. We show that MFA-DVR not only generates more faithful volume rendering results with less memory
footprint, but also performs faster than traditional algorithms when rendering unstructured datasets. MFA-DVR is implemented in the
existing volume rendering pipeline of the Visualization Toolkit (VTK) in order to be accessible by the scientific visualization community.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mfa2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MFA-DVR performance comparision on interpolatin and compression.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mfa1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MFA-DVR high-order interpolation comparing with other linear and non-linear interpolators.
</div>

<iframe width="960" height="480" src="https://www.youtube.com/embed/FHzvs5nITpw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<div class="caption">
    MFA-DVR rendering quality and performance evaluation
</div>

Dataset:
Multiple volumetric dataset with various size.
