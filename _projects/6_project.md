---
layout: page
title: Spatial-Temporal Scientific Data Clustering via Deep Convolutional Neural Network
description: Dimension reduction using convolutional autoencoder for spatial-temporal data classification. (Convolutional Neural Network, Dimension Reduction, Spatial-Temporal Data, Classification)
img: assets/img/water0.png
importance: 6
category: work
---

I explore the usage of deep convolutional neural network for clustering the time steps of a spatial-temporal scientific dataset. The approach first takes the scientific dataset as training data and trains a deep convolutional autoencoder. A low-dimensional feature space or latent space can be extracted by inferencing the encoding part of the network. As a result, each time step is transformed into a feature descriptor that can be compared with each other in the feature space. In this way, we can cluster time steps according to their feature descriptors, and each group of time steps has a similar characterization. We demonstrate the effectiveness of our approach using a real-world simulation dataset of water contamination. Multiple variables and their combinations of this dataset are fed into our approach. The trained network enables the clustering of the time steps and facilitates scientists to examine their large spatial-temporal datasets.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/water1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Encoded latend space representation of water content feature across multiple time steps
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/water2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Latent space of water content and pressure feature.
</div>

we demonstrate the feasibility to use
autoencoder with deep convolutional neural network to cluster
the time steps of a scientific dataset. Our preliminary results
show that feature descriptors can be learned for individual
variable and their combinations for a real-world simulation
data. Each time step can be represented as a set of vectors in
the feature space. Using this representation, we can quantify
the distance between the time steps and cluster them into
different groups, where each group has similar patterns. Our
visualization results qualitatively reveal the difference and the
similarity among different classes.
