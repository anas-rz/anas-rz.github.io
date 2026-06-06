---
layout: page
title: Keras Core Contributions (Backend-Agnostic ML & Vision Models)
description: Contributions to Keras Core including backend-agnostic vision transformer components, example ports, and core API improvements (later migrated into Keras 3).
img: 
importance: 1
category: open-source
related_publications: false
---

# Keras Core Contributions

This project highlights a series of **open-source contributions to Keras Core**, focusing on making deep learning examples and components **backend-agnostic across TensorFlow, JAX, and PyTorch**. These contributions helped shape early multi-backend design patterns that were later **migrated and evolved into Keras 3**.

> Many of these implementations and design patterns were later **shifted into Keras 3**, aligning with its unified multi-backend architecture.

---

## Overview

The contributions include:

* Backend-agnostic implementations of vision and sequence models
* Cross-backend utility functions (e.g., patch extraction for Vision Transformers)
* Migration of research examples into Keras Core
* Improvements to model portability across frameworks
* Fixes and enhancements to core example implementations

These efforts contributed to the transition toward a fully **multi-backend Keras ecosystem**.

---

## Key Technical Contribution Areas

### 1. Cross-Backend Vision Transformer Utilities

A major contribution was implementing **cross-backend patch extraction operations**, enabling Vision Transformer-like models to run consistently across frameworks.

* Implemented backend-agnostic patch extraction in core ops
* Improved compatibility for transformer-based architectures

---

### 2. Porting Research Models to Keras Core

Multiple research models and examples were migrated into Keras Core:

* SimSiam self-supervised learning
* Neural Decision Forests
* Token Learner models
* External Attention mechanisms
* Compact Convolution Transformer (CCT)
* Vision Transformer variants
* DeepLabV3+ segmentation model

---

### 3. Backend-Agnostic Example Frameworks

Converted several educational and research examples into framework-independent implementations:

* Few-shot learning (Reptile algorithm)
* Actor-Critic reinforcement learning (CartPole)
* Time-series anomaly detection
* Image denoising autoencoders
* Keypoint detection pipelines
* Grad-CAM visualization utilities

---

## Merged Pull Requests

Below is a selection of merged contributions:

* Syntax fix in CCT example — PR #898
* Port SimSiam to Keras Core — PR #644
* Port “Visualizing What ConvNets Learn” — PR #640
* Neural Decision Forest port — PR #631
* FixRes Keras Core port — PR #630
* Learnable Resizer (backend-agnostic) — PR #622
* TabTransformer example port — PR #621
* Big Transfer (BiT) port — PR #615
* Digit Addition RNN example — PR #614
* GCAM backend-agnostic implementation — PR #601
* Patch extraction implementation in ops — PR #581
* Backend-agnostic example refactor — PR #567
* Few-shot learning (Reptile) — PR #564
* Keypoint detection backend-agnostic port — PR #546
* DeepLabV3+ conversion — PR #545
* Actor-Critic CartPole — PR #542
* External Attention conversion — PR #529
* Token Learner conversion — PR #528
* Image denoising autoencoder framework — PR #524
* Compact Convolution Transformer conversion — PR #523
* Time-series anomaly detection framework — PR #501
* Vision Transformer without Attention — PR #497

---

## Impact

These contributions helped:

* Strengthen Keras Core’s multi-backend abstraction layer
* Improve portability of research models across frameworks
* Enable reproducible ML examples across TensorFlow, JAX, and PyTorch
* Lay foundational work later integrated into **Keras 3**

---

## Technologies

* Python
* Keras Core
* TensorFlow
* JAX
* PyTorch
* Deep Learning Research Models

---

## Repository

Merged contributions can be explored here:

https://github.com/keras-team/keras-core/pulls?q=is%3Apr+is%3Amerged+author%3Aanas-rz

---

## Notes

These contributions were part of the early evolution of Keras Core and directly influenced the design direction of **Keras 3 multi-backend APIs**.
