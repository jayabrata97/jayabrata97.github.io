---
layout: page
title: Image Style Transfer
description: Generating new images
img: assets/img/starry_night.jpg
importance: 2
category: work
giscus_comments: false
---

Image style transfer is a technique that involves changing the style of an image by applying the graphic features of one image (such as colors, textures, and patterns) onto another, resulting in a brand-new image that amalgamates the content of one image with the elegance of another. The goal of image style transfer is to synthesize a texture from an input image while constraining the texture synthesis in order to preserve the semantic content of a target image. The advanced style transfer techniques can be used for generating new images to study the performance of new algorithms for domain adaption in computer vision in applications like autonomous driving scene understanding in new weathers. 

Neural Style Transfer:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/2_neural_alpha=2_beta=1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left one is content image. Middle one is style image. Right one is output image.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3_neural_alpha=2_beta=1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left one is content image. Middle one is style image. Right one is output image.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/15_neural_alpha=100.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left one is content image. Middle one is style image. Right one is output image.
</div>

Deep Photo Style Transfer:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/input_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/style_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/output_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, there is content image. Middle, there is style image. Right, there is stylized image.
</div>

The code is [here](https://github.com/jayabrata97/IISC_Machine_Learning_E0_270/tree/main/E0-270%20term%20paper/Code).

