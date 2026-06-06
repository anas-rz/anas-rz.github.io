---
layout: page
title: FocalNet – Keras 3 Implementation
description: Keras 3 translation of FocalNet (Focal Modulation Network), an attention-free vision architecture from Microsoft.
img: 
importance: 1
category: open-source
related_publications: false
---

# FocalNet: Keras 3 Translation

This project is a **Keras 3 implementation of FocalNet (Focal Modulation Network)**, an attention-free vision architecture originally released by Microsoft in 2022. FocalNet replaces traditional self-attention mechanisms with focal modulation and achieves competitive or superior performance on multiple vision benchmarks.

---

## Overview

FocalNet introduces a new paradigm in vision modeling by removing explicit self-attention and instead using **focal modulation layers** to capture both local and global context efficiently.

This implementation brings FocalNet into the **Keras 3 multi-backend ecosystem**, making it compatible with TensorFlow, JAX, and PyTorch.

---

## Key Features

* Keras 3 multi-backend implementation
* Attention-free architecture (Focal Modulation)
* Scalable model variants (Tiny → Huge)
* Efficient vision backbone design
* Easy integration into Keras workflows
* Colab-ready example usage

---

## Installation

Clone the repository:

```bash id="focal_install"
git clone https://github.com/anas-rz/focalnet-keras-3.git
cd focalnet-keras-3
```

---

## Usage

```python id="focal_usage"
from focalnet_keras_core import *

model = focalnet_huge_fl3()
```

---

## Model Variants

The implementation supports multiple scalable configurations:

### Tiny / Small / Base

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

### Large / XLarge / Huge

* focalnet_large_fl3
* focalnet_large_fl4
* focalnet_xlarge_fl3
* focalnet_xlarge_fl4
* focalnet_huge_fl3
* focalnet_huge_fl4

---

## Architecture Insight

FocalNet replaces self-attention with:

* Focal Modulation Layers
* Hierarchical feature aggregation
* Efficient spatial context modeling

This design reduces computational complexity while maintaining strong representation power for vision tasks.

---

## Colab Demo

Try the model interactively:

<a target="_blank" href="https://colab.research.google.com/github/anas-rz/focalnet-keras-core/blob/main/colab_usage.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

## Applications

* Image classification
* Vision representation learning
* Efficient transformer alternatives
* Research in attention-free architectures
* Multi-backend deep learning experiments

---

## Technologies

* Python
* Keras 3
* TensorFlow
* JAX
* PyTorch
* Computer Vision
* Deep Learning

---

## Related Work

* Original FocalNet by Microsoft Research
* Paper: https://arxiv.org/abs/2203.11926
* Reference implementation: https://github.com/microsoft/FocalNet/

---

## Repository

https://github.com/anas-rz/focalnet-keras-3

---

## Summary

This project provides a clean and modular Keras 3 implementation of FocalNet, enabling researchers and developers to explore attention-free vision architectures in a modern multi-backend deep learning ecosystem.
