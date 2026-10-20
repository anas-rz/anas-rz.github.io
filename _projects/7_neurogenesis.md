---
layout: page
title: "NeuroGenesis: LLM-Driven Architecture Search"
description: "Reasoning-guided Neural Architecture Search (NAS) using LLMs for systematic hypothesis formation across audio, video, images, and time-series (IEEE QRS 2026)."
importance: 2
category: "Research"
related_publications: true
---

# NeuroGenesis: LLM-Driven Neural Architecture Search

**Stack:** Python, PyTorch, LLMs, AutoML, Neural Architecture Search (NAS)  
**Venue:** IEEE International Conference on Software Quality, Reliability and Security (QRS 2026)  
**Authors:** Muhammad Anas Raza, Niful Islam, Mohammad Wardat

---

## Overview

Traditional Neural Architecture Search (NAS) approaches rely heavily on brute-force random search, reinforcement learning, or genetic algorithms—requiring massive compute clusters and evaluating hundreds of degenerate candidates without semantic reasoning.

**NeuroGenesis** introduces a reasoning-guided NAS paradigm that replaces blind trial-and-error with systematic hypothesis formation, design justification, and iterative architectural refinement using LLMs.

---

## Key Innovations

* **Multimodal Search Space:** Evaluated across **4 distinct data modalities**: audio waveforms, raw video, spatial images, and multivariate time series (MTS).
* **20 Candidate Backbones:** Supports modern backbones across classification, regression, and sequence forecasting.
* **Rapid Prototyping:** Uses calibrated synthetic and toy datasets to explore model configurations at minimal GPU cost before transferring to full-scale datasets.
* **Empirical Validation:** Benchmarked across **8 large real-world user datasets** and **22 specialized benchmarks**, matching or exceeding manually hand-crafted architectures and established AutoML tools (AutoKeras, AutoTS) while slashing total search duration.

