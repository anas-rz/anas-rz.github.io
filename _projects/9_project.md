---
layout: page
title: Evaluating Modern Vision Architectures on 3D Biomedical Data
description: Comparative evaluation of modern vision architectures (MLP-Mixer, FNet, gMLP) on 3D biomedical datasets using adapted 3D model variants.
img: 
importance: 1
category: research
related_publications: false
---

# Evaluating Modern Vision Architectures on 3D Biomedical Data

This project presents a comprehensive **benchmark study of modern vision architectures adapted to 3D biomedical imaging data**. Originally designed for 2D vision tasks, models such as **MLP-Mixer, FNet, and gMLP** were extended to 3D and systematically evaluated on multiple biomedical datasets.

The work was published as a **Colab notebook and Google Slides presentation**, enabling reproducible experimentation and visualization of results.

---

## Overview

Recent advances in vision architectures have shown strong performance on 2D image classification tasks. This project investigates how well these architectures generalize to **3D biomedical imaging data**, where volumetric structure plays a critical role.

Key contributions include:

* Extending 2D vision architectures to 3D inputs
* Designing consistent evaluation pipelines across datasets
* Benchmarking multiple modern architectures under identical settings
* Analyzing performance trade-offs across models and tasks

---

## Evaluated Models

The following architectures were adapted for 3D biomedical data:

* MLP-Mixer (patch-based 3D adaptation)
* FNet (Fourier-based token mixing)
* gMLP (Spatial Gating Unit-based model)

These models were originally designed for 2D vision tasks and modified to handle volumetric inputs.

---

## Datasets

Evaluation was conducted on multiple **MedMNIST3D-style datasets**, including:

* OrganMNIST3D
* NoduleMNIST3D
* FractureMNIST3D
* AdrenalMNIST3D
* VesselMNIST3D
* SynapseMNIST3D

Each dataset represents a different biomedical classification task involving 3D volumetric data.

---

## Key Results

### OrganMNIST3D

* MLP-Mixer: **70.66% Top-1 / 94.43% Top-5**
* FNet: **79.18% Top-1 / 96.72% Top-5**
* gMLP: **82.79% Top-1 / 98.85% Top-5**

---

### NoduleMNIST3D

* MLP-Mixer: **81.94% Top-1 / AUC 80.40**
* FNet: **81.29% Top-1 / AUC 79.69**
* gMLP: **85.16% Top-1 / AUC 85.89**

---

### FractureMNIST3D

* Modified MLP-Mixer: **44.17% Top-1**
* FNet: **82.9% Top-1**
* gMLP: **87.1% Top-1**

---

### AdrenalMNIST3D

* MLP-Mixer: **74.83% Top-1 / AUC 64.93**
* FNet: **80.54% Top-1 / AUC 69.51**
* gMLP: **75.84% Top-1 / AUC 70.73**

---

### VesselMNIST3D

* MLP-Mixer: **89.27% Top-1 / AUC 68.78**
* FNet: **88.74% Top-1 / AUC 80.13**
* gMLP: **90.31% Top-1 / AUC 67.09**

---

### SynapseMNIST3D

* MLP-Mixer: **57.39% Top-1 / AUC 46.55**
* FNet: **73.01% Top-1 / AUC 57.56**
* gMLP: **73.01% Top-1 / AUC 50.0**

---

## Key Insights

* **gMLP consistently performs best** on most 3D biomedical tasks.
* Fourier-based FNet shows strong performance in several datasets.
* MLP-Mixer is competitive but sensitive to task complexity.
* 3D adaptation significantly impacts architecture effectiveness.

---

## Methodology

1. Convert 2D vision architectures to 3D variants
2. Standardize input preprocessing across datasets
3. Train models under comparable conditions
4. Evaluate using Top-1, Top-5, and AUC metrics
5. Compare architectural robustness across tasks

---

## Deliverables

* 📓 Google Colab notebook (reproducible experiments)
* 📊 Presentation slides (visual analysis of results)

---

## Applications

* 3D medical image classification
* Biomedical AI benchmarking
* Architecture evaluation for volumetric data
* Transferability analysis of vision models

---

## Technologies

* Python
* TensorFlow / Keras
* PyTorch (adaptations)
* NumPy
* Medical imaging datasets (MedMNIST3D)
* Deep learning for vision

---

## Summary

This project demonstrates that modern 2D vision architectures can be effectively adapted to 3D biomedical data, with performance varying significantly across architectures. It provides a structured benchmark for understanding how transformer-free models generalize to volumetric medical imaging tasks.
