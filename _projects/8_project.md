---
layout: page
title: FocalNet – TensorFlow Implementation
description: TensorFlow translation of FocalNet (Focal Modulation Network), an attention-free vision architecture by Microsoft.
img: 
importance: 1
category: open-source
related_publications: false
---

# FocalNet: TensorFlow Implementation

This project is a **TensorFlow implementation of FocalNet (Focal Modulation Network)**, an attention-free vision architecture introduced by Microsoft in 2022. FocalNet replaces self-attention with focal modulation, achieving strong performance across multiple vision benchmarks while improving efficiency.

---

## Overview

FocalNet is designed as an alternative to transformer-based attention models. Instead of computing self-attention, it uses:

* Focal modulation layers
* Hierarchical feature aggregation
* Efficient spatial context modeling

This implementation brings FocalNet into the **TensorFlow ecosystem**, enabling seamless integration into TensorFlow-based pipelines and research workflows.

---

## Key Features

* Pure TensorFlow implementation
* Attention-free architecture
* Multiple scalable model variants
* Compatible with Keras-style workflows
* Easy installation via pip
* Research-ready modular design

---

## Installation

```bash id="focal_tf_install"
pip install focalnet-tensorflow
```

---

## Usage

```python id="focal_tf_usage"
from focalnet_tensorflow import *

model = focalnet_huge_fl3()
```

A full usage example is available in:

* `test_notebook_focalnet_tensorflow.ipynb`

---

## Model Variants

The implementation includes a wide range of pretrained-like configurations:

### Small to Base Models

* focalnet_tiny_srf
* focalnet_small_srf
* focalnet_base_srf
* focalnet_tiny_lrf
* focalnet_small_lrf
* focalnet_base_lrf

### Isotropic Variants

* focalnet_tiny_iso_16
* focalnet_small_iso_16
* focalnet_base_iso_16

### Large Scale Models

* focalnet_large_fl3
* focalnet_large_fl4
* focalnet_xlarge_fl3
* focalnet_xlarge_fl4
* focalnet_huge_fl3
* focalnet_huge_fl4

---

## Architecture Insight

FocalNet replaces traditional self-attention with:

* Focal modulation blocks for feature interaction
* Multi-scale context aggregation
* Efficient spatial reasoning without quadratic attention cost

This makes it a strong alternative to transformer-based vision architectures.

---

## Todo

* [ ] Test ported weights
* [ ] Create a PR at original FocalNet repository

---

## Applications

* Image classification
* Vision representation learning
* Efficient CNN/Transformer alternatives
* Research in attention-free architectures
* TensorFlow-based deployment pipelines

---

## Technologies

* TensorFlow
* Keras
* Python
* Computer Vision
* Deep Learning

---

## Related Work

* Original FocalNet (Microsoft Research)
* Paper: https://arxiv.org/abs/2203.11926
* GitHub: https://github.com/microsoft/FocalNet/

---

## Repository

https://github.com/anas-rz/focalnet-tensorflow

---

## Summary

This project provides a clean TensorFlow translation of FocalNet, enabling researchers to explore attention-free vision models within the TensorFlow ecosystem while maintaining compatibility with modern deep learning workflows.
