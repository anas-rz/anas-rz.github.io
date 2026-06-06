---
layout: page
title: K3 Addons
description: Multi-backend extensions for Keras 3 featuring advanced layers, attention mechanisms, losses, and activations.
img: assets/img/k-addons.png
importance: 1
category: open-source
related_publications: false
---

# K3 Addons

K3 Addons is an open-source extension library for Keras 3 that provides advanced machine learning components not included in the core framework. The project enables researchers and practitioners to leverage innovative neural network layers, attention mechanisms, loss functions, and activation functions while maintaining compatibility across Keras 3's multiple backends.

<!-- <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/k3-addons/logo.png" title="K3 Addons" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    K3 Addons extends Keras 3 with cutting-edge deep learning components and multi-backend compatibility.
</div> -->

## Overview

Keras 3 introduced a powerful multi-backend ecosystem, allowing developers to build models across TensorFlow, JAX, and PyTorch backends. However, many specialized techniques used in research and industry are too niche to be included in the core Keras APIs.

K3 Addons bridges this gap by providing implementations of state-of-the-art attention mechanisms, advanced pooling layers, normalization techniques, custom losses, and novel activation functions while preserving the multi-backend philosophy of Keras 3.

## Motivation

The goal of K3 Addons is to:

* Expand the Keras 3 ecosystem
* Provide reusable research components
* Support multiple deep learning backends
* Accelerate experimentation with modern architectures
* Enable rapid prototyping of advanced neural networks

## Key Features

* Multi-backend compatibility
* Advanced attention mechanisms
* Adaptive pooling layers inspired by PyTorch
* Specialized normalization layers
* Modern loss functions
* Novel activation functions
* Research-friendly architecture
* Easy installation through PyPI

## Installation

```bash
pip install k3-addons
```

## Technology Stack

* Python
* Keras 3
* TensorFlow
* JAX
* PyTorch
* NumPy

## Implemented Components

### Adaptive Pooling Layers

K3 Addons provides multi-backend implementations inspired by PyTorch:

* AdaptiveAveragePooling1D
* AdaptiveMaxPooling1D
* AdaptiveAveragePooling2D
* AdaptiveMaxPooling2D
* Maxout Layer

<!-- <div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/k3-addons/pooling.png" title="Pooling Layers" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/k3-addons/maxout.png" title="Maxout Layer" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Adaptive pooling and Maxout implementations designed for multi-backend Keras workflows.
</div> -->

### Normalization Layers

* InstanceNormalization

Provides instance-level normalization for improved training stability in computer vision and generative models.

### Attention Mechanisms

One of the largest components of K3 Addons is its collection of modern attention modules.

Implemented attention layers include:

* Double Attention
* AFT Full (Attention-Free Transformer)
* Channel Attention
* Spatial Attention
* ECA Attention
* External Attention
* Residual Attention
* MobileViT Attention
* BAM Block
* CBAM
* MobileViTv2 Attention
* ParNet Attention
* SimAM

<!-- <div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/k3-addons/attention1.png" title="Attention Mechanisms" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/k3-addons/attention2.png" title="Vision Attention" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/k3-addons/attention3.png" title="Transformer Attention" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Collection of modern attention modules for computer vision, transformers, and deep learning research.
</div> -->

## Loss Functions

K3 Addons includes specialized loss functions commonly used in research and production systems:

* ContrastiveLoss
* GIoULoss
* PinballLoss
* SigmoidFocalCrossEntropy
* WeightedKappaLoss
* pairwise_distance
* pinball_loss

These losses support tasks such as:

* Object Detection
* Metric Learning
* Ordinal Classification
* Quantile Regression
* Imbalanced Classification

## Activation Functions

Implemented activation functions include:

* HardShrink
* LiSHT
* Mish
* Snake
* TanhShrink

These activations provide alternatives to ReLU-based architectures and enable experimentation with emerging neural network designs.

## Example Usage

```python
import keras
import k3_addons as k3a

layer = k3a.layers.ECAAttention()
```

```python
loss = k3a.losses.ContrastiveLoss()
```

```python
activation = k3a.activations.mish
```

## Impact

K3 Addons enables researchers and developers to:

* Prototype new architectures rapidly
* Use advanced attention mechanisms without custom implementations
* Experiment across TensorFlow, JAX, and PyTorch backends
* Reuse modern deep learning components through a unified API

## Open Source Contribution

This project contributes to the broader Keras ecosystem by making advanced machine learning techniques accessible through a consistent, multi-backend interface.

## Future Roadmap

Planned future enhancements include:

* Additional transformer modules
* Graph neural network layers
* Advanced optimization algorithms
* Vision-language model components
* Time-series specific layers
* Expanded research-oriented APIs

## Repository

GitHub Repository:

https://github.com/anas-rz/k3-addons

## Highlights

* Multi-backend Keras 3 extension library
* State-of-the-art attention implementations
* PyTorch-inspired adaptive pooling layers
* Advanced losses and activations
* Research-focused open-source contribution
