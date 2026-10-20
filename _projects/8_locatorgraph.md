---
layout: page
title: "LocatorGraph: GNN Fault Localization for DL Programs"
description: "Novel GNN framework converting sequence model code into TraceGraphs to localize structural and runtime deep learning bugs (Empirical Software Engineering 2025)."
importance: 3
category: "Research"
related_publications: true
---

# LocatorGraph: GNN Fault Localization for Deep Learning Programs

**Stack:** Python, Graph Neural Networks, PyTorch Geometric, AST Analysis  
**Journal:** Empirical Software Engineering (EMSE), 30(5):119, 2025  
**DOI:** [10.1007/s10664-025-10666-6](https://doi.org/10.1007/s10664-025-10666-6)  
**Authors:** Muhammad Anas Raza, Mohammad Wardat

---

## Overview

Localizing bugs in deep learning code is notoriously difficult due to complex dataflow dependencies, dynamic tensor shapes, and silent runtime dimension mismatches. 

**LocatorGraph (LG)** introduces a Graph Neural Network-based fault localization framework that parses sequence-based model code (RNNs, LSTMs, GRUs, Transformers, gMLP) into structured **TraceGraphs** to identify and pinpoint root causes of failure.

---

## Empirical Evaluation (152 Sequence Models)

* **Bug Identification:** Achieved **89.46% AUC** and **81.34% F1-score** in classifying whether a sequence model implementation contains structural flaws.
* **Feature Inspection:** Achieved **91.19% accuracy** and **89.68% F1-score** on inspecting graph-based computation features.
* **Faulty Node Pinpointing:** Localized exact bug-causing nodes within computation graphs with **81.54% accuracy** and **79.98% F1-score**, consistently outperforming baseline spectra-based and static fault localization techniques.

