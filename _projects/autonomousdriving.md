---
layout: page
title: Environment Perception in Autonomous Driving
description: interpreting high-dimensional feature spaces of convolutional neural networks
img: assets/img/project_profiles/autonomousdriving.jpg
importance: 3
category: work
---

As part of a research group at [Mercedes Benz](https://www.mercedes-benz.com/en/) (lead by [Uwe Franke](https://ieeexplore.ieee.org/author/37283450400)) that works on image understanding and environment perception for autonomous driving, I trained deep convolutional neural networks for semantic image segmentation. In particular, using the [Cityscapes data set](https://www.cityscapes-dataset.com/), I developed algorithms for the interpretation and visualization of high-dimensional feature spaces that allow the system to predict subclasses of objects even though it has never been trained on them.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/EnvironmentPerception3.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview: simplified overview of an extraction framework to create data bases for similarity searches of pooled feature vectors.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/EnvironmentPerception2.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example: Visualization of activations of different convolutional neural network layers.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/EnvironmentPerception1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example: Predictions of subclasses by interpreting feature spaces from different network layers.
</div>
