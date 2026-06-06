---
layout: page
title: Deep Forgery Detector
description: Modular framework for benchmarking and deploying deepfake video detection models developed at SMILES Lab, Oakland University.
img: 
importance: 1
category: research
related_publications: false
---

# Deep Forgery Detector

Deep Forgery Detector is an extensible and modular framework designed for **deploying, benchmarking, and comparing deepfake detection algorithms in videos and visual data**. The project was developed during research work at the **SMILES Lab, Oakland University**, with a focus on enabling rapid experimentation with state-of-the-art forgery detection methods.

---

## Overview

The rapid rise of deepfake generation techniques has created a strong need for reliable and scalable detection systems. Deep Forgery Detector addresses this challenge by providing a unified framework that allows researchers to:

* Integrate new deepfake detection models quickly
* Benchmark multiple architectures under consistent evaluation settings
* Run reproducible experiments on video and image datasets
* Extend the framework for future research contributions

The system is designed with modularity and extensibility as its core principles.

---

## Key Features

* Modular architecture for plug-and-play model integration
* Support for multiple deepfake detection models
* Benchmarking pipeline for fair comparison of methods
* Video-based and frame-based evaluation support
* Extensible dataset handling system
* Research-friendly design for rapid experimentation
* Clean separation between data loading, model, and evaluation layers

---

## System Design

The framework follows a structured pipeline:

* Data preprocessing and frame extraction
* Model inference (deepfake classifiers)
* Temporal and spatial feature aggregation
* Evaluation and benchmarking metrics
* Result visualization and comparison

This design ensures consistency across different research models while maintaining flexibility.

---

## Research Context

This work was carried out at the **SMILES Lab, Oakland University**, focusing on improving reproducibility and scalability in deepfake detection research. The framework was designed to support both:

* Classical deep learning-based detectors
* Emerging transformer-based video analysis models

---

## Applications

Deep Forgery Detector can be used for:

* Deepfake video detection research
* Benchmarking detection algorithms
* Media authenticity verification
* Academic research in computer vision security
* Dataset evaluation and model comparison

---

## Impact

This framework enables:

* Faster prototyping of deepfake detection models
* Standardized evaluation across research methods
* Easier reproducibility of published approaches
* Extension of state-of-the-art detection pipelines

---

## Technologies

* Python
* PyTorch / TensorFlow (depending on model integration)
* OpenCV
* NumPy
* Deep Learning for Video Analysis
* Computer Vision pipelines

---

## Affiliation

Developed at:

**SMILES Lab**
Oakland University

---

## Future Enhancements

* Integration of transformer-based video models
* Real-time deepfake detection pipeline
* Web-based demo interface
* Distributed benchmarking system
* Support for multimodal (audio-visual) deepfake detection

---


## Summary

Deep Forgery Detector provides a unified and extensible research framework for advancing the field of deepfake detection, enabling reproducible benchmarking and rapid integration of emerging detection models.
