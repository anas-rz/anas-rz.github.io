---
layout: page
title: "K3IM: Keras 3 Image Models Zoo"
description: "Comprehensive model zoo featuring 50+ modern vision and spatiotemporal architectures across 1D, 2D, and 3D data modalities on TensorFlow, PyTorch, and JAX."
img: assets/img/k3im.png
importance: 3
category: "ML Systems"
related_publications: false
---

# K3IM: Keras 3 Image Models Zoo

**Stack:** Keras 3, PyTorch, TensorFlow, JAX, Python  
**Code:** [github.com/anas-rz/k3im](https://github.com/anas-rz/k3im)

---

## Overview

**K3IM** is an open-source model zoo built for **Keras 3**, providing a unified library of modern deep learning vision architectures supporting **1D signals, 2D images, 3D volumetric scans, and spatiotemporal video data** across all three major ML backends: **TensorFlow, PyTorch, and JAX**.

---

## Key Architectures Implemented from Scratch

* **Vision Transformers & Attention:**
  * **CaiT (Class-Attention in Image Transformers):** Layer-scale stabilization and dedicated class-attention stages.
  * **Compact Convolution Transformer (CCT):** 1D, 2D, and 3D implementations for sample-efficient small-dataset vision learning.
  * **CrossViT & DeepViT:** Dual-branch multi-scale token fusion and re-attention mechanics.
  * **SimpleViT:** Modern minimalist ViT baseline with FFT, patch dropout, and register tokens.
  * **Swin Transformer:** Hierarchical shifted-window self-attention.
* **All-MLP and Hybrid Architectures:**
  * **MLP-Mixer (1D, 2D, 3D):** Pure multi-layer perceptron architecture with automated pretrained weight downloaders.
  * **gMLP (1D, 2D, 3D):** Spatial Gating Units (SGU) for attention-free sequence and spatial mixing.
  * **ConvMixer (1D, 2D, 3D):** Isotropic convolutional mixing with depthwise-separable blocks.
* **Specialized Modulations & Fourier Networks:**
  * **Fourier Net (FNet):** 2D Fast Fourier Transform replacing self-attention with unparameterized 2D FFT.
  * **FocalNet:** Focal modulation mechanisms capturing local and global context without quadratic attention complexity.
  * **External Attention Network (EA-Net):** Linear complexity external memory attention.
  * **TokenLearner:** Adaptive token reduction for high-resolution vision and video streams.

