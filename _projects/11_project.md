---
layout: page
title: Full stack website for covercrop prediction and result visualization.
description: AngularJS front-end. Spring boot back-end with Apsim simulation running on the back-end. (AngularJS, Spring Boot, D3.js)
img: assets/img/covercrop.png
importance: 11
category: work
---

This tool is designed to farmer information on what to expect from your cover crop, right at their own farms. Visit the website [here](https://covercrops.unl.edu). The press covering this project can be found [here](https://cropwatch.unl.edu/2022/cover-crop-biomass-calculator-available-nebraska)

D3.js is used on the front-end AngularJS framework for interactive UI. Configuration is sent to back-end where the simulation software is running using such updated configuration. Simulation results are saved in the database on the back-end for future queries. Simulation results are also delivered to the front-end for analysis and visualization.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/covercrop1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Covercrop biomass calculaor website.
</div>

The goal of the biomass calculator is to provide producers, researchers and other agriculture professionals with realistic, data-driven predictions to address the challenges presented in the winter growing period. 
