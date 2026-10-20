---
layout: page
title: "Keras-Climate & keras-geo"
description: "Multi-backend framework for Earth observation, satellite imagery, climate modeling, and weather nowcasting in Keras 3."
importance: 4
category: "ML Systems"
related_publications: false
---

# Keras-Climate & keras-geo: Earth Observation in Keras 3

**Stack:** Keras 3, PyTorch, TensorFlow, JAX, Python  
**Code:** [github.com/anas-rz/keras-climate](https://github.com/anas-rz/keras-climate)  
**Docs:** [anas-rz.github.io/keras-climate/](https://anas-rz.github.io/keras-climate/)

---

## Overview

**Keras-Climate** is a modern, backend-agnostic framework built on Keras 3 dedicated to **Earth observation, climate modeling, weather forecasting, and remote sensing**. It allows scientists and ML engineers to train and evaluate geospatial models seamlessly on PyTorch, TensorFlow, or JAX.

---

## Key Capabilities

* **Multispectral Remote Sensing:** Implemented `UNet` and `SegFormer` architectures specialized for multi-band satellite data (RGB + Near-Infrared).
* **Long-Term Multivariate Climate Forecasting:** Configured `PatchTST` for multi-variable atmospheric and climate sequences (e.g., input seq_len=336, forecast horizon pred_len=96 across 7 channels).
* **Radar & Precipitation Nowcasting:** `ConvLSTMNowcaster` for spatiotemporal radar and weather nowcasting.
* **Geospatial Foundation Model:** `PrithviClassifier`, integrating the NASA/IBM geospatial foundation model directly into the multi-backend Keras 3 ecosystem with automated weight porting and parity checks.
* **keras-geo:** Companion library porting key TorchGeo modules into multi-backend Keras 3 with dedicated ViT weight converters.

