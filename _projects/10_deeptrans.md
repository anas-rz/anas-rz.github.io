---
layout: page
title: "DeepTrAnS: Unsupervised Server Telemetry Anomaly Detection"
description: "Mixer-based unsupervised anomaly detection framework for high-dimensional server telemetry, achieving 99.88% precision and 99.81% F1-score (IEEE ICSC 2025)."
importance: 5
category: "Research"
related_publications: true
---

# DeepTrAnS: Time-Series Anomaly Detection for Server Telemetry

**Stack:** Python, PyTorch, MLP-Mixer, Time-Series Processing, AIOps  
**Conference:** IEEE International Intelligent Cybersecurity Conference (ICSC 2025)  
**DOI:** [10.1109/ICSC65596.2025.11139978](https://doi.org/10.1109/ICSC65596.2025.11139978)  
**Authors:** Muhammad Anas Raza, Mohammad Wardat, Anyi Liu

---

## Overview

High-dimensional server telemetry (tracking CPU load, memory paging, I/O rates, and network saturation) exhibits complex temporal correlations and sudden regime shifts. 

**DeepTrAnS** is a pure MLP-Mixer-based unsupervised anomaly detection framework that deploys a two-phase reconstruction strategy to learn normal infrastructure operational baselines without needing labeled anomalous training samples.

---

## Benchmark Performance

Evaluated against comprehensive production server telemetry datasets:
* **Detection Accuracy:** Achieved **99.88% Precision**, **99.73% Recall**, **99.86% AUC**, and **99.81% F1-score**.
* **Baseline Comparisons:** Drastically outperformed established baselines:
  * TranAD (F1: 96.04%)
  * DAGMM (F1: 93.99%)
  * OmniAnomaly (F1: 90.36%)
  * MERLIN (F1: 38.42%)

