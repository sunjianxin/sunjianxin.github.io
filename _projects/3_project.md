---
layout: page
title: 3D Learning from Point Cloud and Mesh
description: RANSAC-based marching ring for 3D cylinder learning to approximate 3D shape and perform 3D semantic segmentation. (OpenGL, OpenCV, Point cloud, Point Cloud Library (PCL), Microsoft Kinect, C/C++)
img: assets/img/tree0.png
importance: 3
category: work
---

RANSAC Marching Ring, RANSAC-MR is a method to model long 3D object into parametric surface and perform segmentations. A 2D RANSAC circle model is calculated from the prejected points withing the range of the marching ring. The final 3D object can be modeled by projecting back the 2D circle to 3D space. 

This method is specially suitable to model tree strucutural objects which gives promising protental to arguicalture automation usint robot.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tree1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Tree trunk modeling using proposed RANSAC-based marching ring and main branch segmentation.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tree2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Tree trunk modeling and main branch segmentation on various apple tree samples.
</div>

Using RmdnCache gives the lowest microblock cache miss rate and input latency comparing to other prefetching algorithms.
