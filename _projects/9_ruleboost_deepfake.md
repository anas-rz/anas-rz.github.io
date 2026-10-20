---
layout: page
title: "RuleBoost & Multimodal Deepfake Forensics"
description: "Neuro-symbolic and audio-visual deepfake detection architectures evaluated on 100K+ videos (IEEE IJCB 2024 Best Poster Award & CVPRW 2023)."
importance: 4
category: "Research"
related_publications: true
---

# RuleBoost & Multimodal Deepfake Forensics

**Stack:** PyTorch, TensorFlow, Vision Transformers, MLP-Mixer, gMLP, Audio-Visual Fusion, Neuro-Symbolic AI  
**Awards:** IEEE IJCB 2024 Best Poster Award  
**Dataset Scale:** Benchmarked on 100K+ manipulated videos across DFDC, FaceForensics++, FakeAVCeleb, and WLDR

---

## Core Contributions

### 1. RuleBoost: Neuro-Symbolic Deepfake Detection (IEEE IJCB 2024 - Best Poster Award)
* Fuses perceptual deep learning representations (gMLP, ViT, TokenLearner) with explicit geometric facial knowledge rules extracted from biological landmark vocabularies.
* Achieved state-of-the-art **96.19% AUC on World Leaders Dataset (WLDR)** and **95.44% AUC on FaceForensics++**, providing unmatched robustness against unseen compression artifacts and extreme facial angles.

### 2. Multimodaltrace (CVPR Workshops 2023 - 129 Citations)
* Explored joint audio-visual representation learning leveraging synchronized acoustic embeddings and dynamic facial motion features.
* Achieved **92.9% accuracy on FakeAVCeleb**, surpassing leading multimodal ensembles by 3.9% and single-modality baselines by over 16%.

### 3. HolisticDFD (Information Sciences 2023 - 45 Citations)
* Designed a holistic intermediate fusion transformer uniting spatial, temporal, and spatiotemporal representations.
* Achieved **0.926 (92.6%) AUC on DFDC** while operating with **only 3% of the parameters** required by competing models.

