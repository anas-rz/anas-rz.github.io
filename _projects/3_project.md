---
layout: page
title: K3IM – Keras 3 Image Models
description: A comprehensive multi-backend model zoo for image, 1D, 3D, and video classification using Keras 3.
img: assets/img/k3im.png
importance: 1
category: open-source
related_publications: false
---

# K3IM: Keras 3 Image Models

K3IM is a large-scale model zoo built on top of **Keras 3**, providing a wide collection of classification architectures for **1D signals, 2D images, 3D volumes, and video/spatiotemporal data**. It is designed to work seamlessly across multiple backends including TensorFlow, PyTorch, and JAX, enabling flexible experimentation and research across different machine learning ecosystems.

<!-- <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/k3im/banner.png" title="K3IM Banner" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    K3IM provides a unified ecosystem of modern deep learning architectures across multiple data modalities.
</div> -->

## Overview

K3IM brings together a wide range of modern neural network architectures, including:

* Vision Transformers (ViT, Swin, DeepViT, CaiT)
* MLP-based architectures (MLP-Mixer, gMLP)
* Convolution-Transformer hybrids (CCT, ConvMixer)
* Attention-based models (CrossViT, External Attention Networks)
* Fourier and token-based architectures
* 1D, 2D, and 3D model variants

It enables researchers and practitioners to quickly deploy and compare state-of-the-art architectures across different domains.

## Key Features

* Multi-backend support (TensorFlow, PyTorch, JAX)
* Unified API across 1D, 2D, and 3D models
* Extensive transformer-based architectures
* Lightweight and efficient convolutional hybrids
* Prebuilt models for rapid experimentation
* Video and spatiotemporal model support
* Modular design for research extensibility

## Installation

```bash id="k3im_install"
pip install k3im --upgrade
```

## Backend Configuration

K3IM supports multiple backends via Keras 3:

```python id="backend_setup"
import os
os.environ["KERAS_BACKEND"] = "jax"  # or "tensorflow" or "torch"
```

> Ensure the backend is set **before importing Keras or K3IM**.

## Model Families

K3IM includes a wide range of architectures:

### Vision Transformers

* Vision Transformer (ViT)
* DeepViT
* Swin Transformer
* CaiT (Class-Attention in Image Transformers)
* CrossViT
* Simple ViT variants

### Convolution-Transformer Hybrids

* Compact Convolution Transformer (CCT)
* ConvMixer (1D / 2D / 3D)
* Focal Modulation Networks

### MLP-Based Models

* MLP-Mixer (1D/2D/3D)
* gMLP
* Token Learner models

### Attention-Based Models

* External Attention Networks (EANet)
* FNet (Fourier-based attention replacement)

## Architecture Highlights

### Compact Convolution Transformer (CCT)

Combines convolutional feature extraction with transformer encoders for efficient learning.

```python
from k3im.cct import CCT

model = CCT(
    input_shape=(28, 28, 1),
    num_heads=8,
    projection_dim=32,
    kernel_size=3,
    stride=3,
    padding=2,
    transformer_units=[16, 32],
    transformer_layers=2,
    num_classes=10,
)
```

### ConvMixer

A fully convolutional architecture inspired by ViT and MLP-Mixer ideas.

```python
from k3im.convmixer import ConvMixer

model = ConvMixer(
    image_size=28,
    filters=64,
    depth=8,
    kernel_size=3,
    patch_size=2,
    num_classes=10,
    num_channels=1
)
```

### Vision Transformer (ViT)

```python
from k3im.vit_1d import ViT1DModel

model = ViT1DModel(
    seq_len=500,
    patch_size=20,
    num_classes=10,
    dim=32,
    depth=3,
    heads=8,
    mlp_dim=64,
)
```

### Swin Transformer

Hierarchical transformer with shifted window attention.

```python
from k3im.swint import SwinTModel

model = SwinTModel(
    img_size=28,
    patch_size=7,
    embed_dim=32,
    num_heads=4,
    window_size=4,
    shift_size=2,
    num_classes=10,
)
```

### MLP-Mixer

Pure MLP-based architecture for vision tasks.

```python
from k3im.mlp_mixer import mixer_b16_224

model = mixer_b16_224(pretrained=True)
```

## Supported Architectures (Full List)

### Attention & Transformer Models

* CaiT
* CrossViT
* DeepViT
* Swin Transformer
* FNet
* External Attention Networks

### MLP-Based Models

* MLP-Mixer (1D/2D/3D)
* gMLP

### Convolution-Based Models

* ConvMixer (1D/2D/3D)
* CCT (1D/2D/3D)

### Specialized Models

* Token Learner ViT
* Simple ViT variants
* ViT with FFT
* ViT with Patch Dropout
* ViT with Register Tokens

## Usage Workflow

### 1. Use Prebuilt Models

```python
from k3im.cross_vit import CrossViT

model = CrossViT(
    image_size=28,
    num_classes=10,
    sm_dim=32,
    lg_dim=42,
)
```

### 2. Customize Architectures

All models are modular and allow customization of:

* Depth
* Embedding dimensions
* Attention heads
* Patch sizes
* Dropout rates

### 3. Multi-Backend Execution

```python
import os
os.environ["KERAS_BACKEND"] = "torch"
```

## Supported Data Types

* 1D time-series signals
* 2D images
* 3D medical/scientific volumes
* Video sequences (spatiotemporal modeling)

## Applications

* Image classification
* Video classification
* Time-series classification
* Medical imaging
* Scientific simulations
* Remote sensing

## Impact

K3IM enables:

* Rapid prototyping of SOTA architectures
* Cross-framework reproducibility
* Unified experimentation across modalities
* Research acceleration in vision and sequence modeling

## Repository

GitHub:

https://github.com/anas-rz/k3im

## Future Work

* Vision-language model extensions
* Self-supervised learning models
* Larger pretrained model zoo
* Efficient transformer variants
* GPU-optimized inference pipelines

## Acknowledgements

K3IM builds upon the advancements in Vision Transformers, MLP architectures, convolutional networks, and Keras 3 multi-backend ecosystem.
