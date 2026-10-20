---
layout: page
title: "K3 Addons: Advanced Multi-Backend Components"
description: "Specialized neural network layers, attention mechanisms (MobileViT, CBAM, ECA), and custom loss functions engineered for Keras 3."
img: assets/img/k-addons.png
importance: 5
category: "ML Systems"
related_publications: false
---

# K3 Addons: Extensions for Keras 3

**Stack:** Keras 3, PyTorch, TensorFlow, JAX, Python  
**Code:** [github.com/anas-rz/k3-addons](https://github.com/anas-rz/k3-addons)

---

## Overview

**K3 Addons** extends the core Keras 3 framework with cutting-edge deep learning layers, attention blocks, and advanced training objectives that maintain full compatibility across TensorFlow, PyTorch, and JAX.

---

## Key Modules

* **Attention Blocks:** MobileViT Attention, CBAM (Convolutional Block Attention Module), Efficient Channel Attention (ECA), and Squeeze-and-Excitation.
* **Specialized Layers:** Parity-matched adaptive pooling layers (`AdaptiveAvgPool1D/2D/3D`, `AdaptiveMaxPool1D/2D/3D`), DropPath / Stochastic Depth, and Spectral Normalization.
* **Loss Functions & Metrics:** Generalized IoU (GIoU), Complete IoU (CIoU), Sigmoid Focal Cross-Entropy, and Triplet Margin Loss with online hard-negative mining.
* **Parity & Tests:** Cross-backend numerical parity suites verified on CPU and GPU against reference PyTorch and TensorFlow implementations.

