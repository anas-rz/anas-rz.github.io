---
layout: page
title: "timm.cpp: Vision Model Inference in C++"
description: "High-performance zero-dependency C++17 inference engine executing PyTorch/timm models via GGUF/ggml with up to 25.8x faster cold start."
importance: 1
category: "ML Systems"
related_publications: false
---

# timm.cpp: High-Performance Vision Inference in C++

**Stack:** C++17, ggml, GGUF, PyTorch, Python, timm, CMake, Docker, CUDA, Metal, Vulkan  
**Status:** Ongoing Engine Development & Tool Paper

---

## Overview

`timm.cpp` is a high-performance C++ inference engine (`libtimm_cpp`) running PyTorch/timm computer vision models via GGUF and ggml with **zero Python dependency** at runtime. Designed specifically for low-latency edge deployment, serverless cold-start optimization, and embedded systems, it eliminates Python runtime overhead completely.

---

## Key Highlights & Achievements

* **106 Vision Architectures Hand-Ported:** Fully ported and validated 106 vision model families including ConvNeXt, ViT/DeiT3, Swin Transformer, ResNet, LeViT, EfficientNet, CaiT, HRNet, CrossViT, MobileNetV3/V5, MetaFormer, and MLP-Mixer.
* **Strict Numerical Parity:** Achieves strict numerical parity against PyTorch references with mean **Cosine Similarity $\ge 0.999997$**.
* **Up to 25.8× Faster Cold-Start Latency:** Achieved up to 25.8× faster cold-start load times compared to PyTorch (e.g., 95 ms vs. 2,453 ms on LeViT; 99 ms vs. 1,667 ms on ResNet-18) leveraging zero-copy POSIX `mmap` and eliminating dynamic Python object initialization overhead.
* **Calibrated Mixed-Precision Quantization (`timm-quantize`):** Implemented sensitivity-aware mixed-precision quantization (`f16`, `q8_0`, `q4_0`, `q4_k`) using Pearson drift calibration on unlabelled calibration sets; compresses weights by **3.4× to 5.8×** (e.g., ResNet-50 from 97 MB down to 14–24 MB) while preserving 98%+ agreement with F32.
* **Embedded HTTP Microservice (`timm-server`):** Built a standalone C++ inference server (style of `llama-server`) featuring an embedded zero-dependency Web UI, REST endpoints (`/v1/classify`, `/v1/embeddings`, `/v1/features`), Prometheus `/metrics`, multi-model LRU memory eviction, and dynamic bucketed graph batching (`ggml_gallocr`).
* **Multi-Backend Hardware Acceleration:** Supports CPU (SIMD AVX2, AVX-512, ARM NEON with llamafile sgemm kernels), NVIDIA CUDA (cuBLAS), Vulkan, Apple Metal, Intel SYCL, and AMD HIP/ROCm.

