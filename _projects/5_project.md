---
layout: page
title: Graph embedding for software source code analytics
description: Deep learning graph embedding is utilized to extract insightful feature from complex call graph to lower-dimensional space for similarity measurement. **(Graph Neural Network, Dimension Reduction, Data Visualization)**
img: assets/img/softvis0.png
importance: 6
category: work
---

Eye tracking is a frequently used technique to collect
data capturing users’ strategies and behaviors in processing
information. Understanding how programmers navigate through
a large number of classes and methods to find bugs is important
to educators and practitioners in software engineering. However,
the eye tracking data collected on realistic codebases is massive
compared to traditional eye tracking data on one static page. The
same content may appear in different areas on the screen with
users scrolling in an Integrated Development Environment (IDE).
Hierarchically structured content and fluid method position
compose the two major challenges for visualization. We present
a dual-space analysis approach to explore eye tracking data
by leveraging existing software visualizations and a new graph
embedding visualization. We use the graph embedding technique
to quantify the distance between two arbitrary methods, which
offers a more accurate visualization of distance with respect to the
inherent relations, compared with the direct software structure
and the call graph. The visualization offers both naturalness and
readability showing time-varying eye movement data in both
the content space and the embedded space, and provides new
discoveries in developers’ eye tracking behaviors.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/softvis1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Tree trunk modeling using proposed RANSAC-based marching ring and main branch segmentation.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/softvis2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Tree trunk modeling and main branch segmentation on various apple tree samples.
</div>

The visualization and clustering results
provide an intuitive and effective way of understanding reading
patterns, such as whether participants follow the tree or call
graph structure and how participants generally navigate to the
bug location and in what sequence. Our visualization uses
the eye trace of the software system as its use case, but it
has the potential of applications in other domains as well.
For example, in social science, we can visualize the pattern
of a person getting himself into a social network, suggesting
his social skills or personality. Similarly, we can investigate
the pattern of how information or news gets spread. In this
paper, we are primarily concerned with eye tracking data for
debugging patterns and efficiency.
