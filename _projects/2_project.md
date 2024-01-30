---
layout: page
title: Capsule Network
description: Image classification with capsule network
img: assets/img/Capsule_Network.png
importance: 2
category: Computer Vision
related_publications: false
---

A Capsule Network (**CapsNet**) is a type of artificial neural network proposed by Geoffrey Hinton and his team. In a **CapsNet**, a capsule is a group of neurons whose activity vector represents the instantiation parameters of a specific type of entity such as an object or an object [part](https://arxiv.org/abs/1710.09829). The length of the activity vector is used to represent the probability that the entity exists, and its orientation represents the instantiation parameters. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Capsule_Network.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Dynamic routing is a key component of Capsule Networks. It determines the modification of weights in the network. This defines the strategy for assigning weights to the neurons’ connections. A Capsule Network adjusts the weights such that a low-level capsule is strongly associated with high-level capsules that are in its proximity. In the context of dynamic routing, lower capsules send data to the most suitable parent capsule based on dot product. The parent capsule is chosen through an agreement mechanism, utilizing the highest dot product between prediction vectors from lower capsules and the weight matrix. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Digit_recogniser.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Capsule_Decoder.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The dynamic routing algorithm by agreement allows to train the CapsNet. The most important idea is that similarity between input and output is measured as dot product between input and output of a capsule and then routing coefficient is updated correspondingly. By allowing the network to iteratively refine the coupling coefficients between capsules based on the agreement of their pose parameters, capsules enable dynamic routing. As a result, CapsNets can better recognize intricate patterns in data, capture complex spatial hierarchies, and improve generalization. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Digit_reconstruction.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MNIST digit reconstruction with CapsNet
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/MNIST_recognition.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Real-time hand written digit classification with CapsNet
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/CIFAR10_Classification.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Confusion matrix for CIFAR10 classification with CapsNet
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/CIFAR10_class.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Real-time image classification with CapsNet
</div>

The code is [here](https://github.com/jayabrata97/IISC_Machine_Learning_E0_270/tree/main/Final%20project/CapsNet/code).