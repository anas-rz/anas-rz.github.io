---
layout: page
title: "K3Node: Multi-Backend Graph Neural Networks"
description: "High-performance GNN library achieving 100% public API parity with PyTorch Geometric across TensorFlow, PyTorch, and JAX with 700+ tests per backend."
importance: 2
category: "ML Systems"
related_publications: false
---

# K3Node: Multi-Backend Graph Neural Networks for Keras 3

**Stack:** Keras 3, PyTorch, TensorFlow, JAX, Python  
**Code:** [github.com/anas-rz/k3-node](https://github.com/anas-rz/k3-node)

---

## Overview

**K3Node** is a next-generation Graph Neural Network (GNN) library designed to achieve **100% public API parity with PyTorch Geometric (PyG)**, fully executable across **TensorFlow, PyTorch, and JAX** with native GPU and TPU acceleration through Keras 3.

---

## Architectural Highlights

* **65+ Convolution Layers:** Implemented core and advanced message-passing operators including `GCNConv`, `GATv2Conv`, `TransformerConv`, `GPSConv`, `PNAConv`, `SchNet`, `DimeNetPlusPlus`, and `ViSNet`.
* **26 Aggregation & 31 Pooling Operators:** Advanced graph pooling schemes including hierarchical coarsening (TopK, SAG, ASAP, EdgePooling) and 3D spatial voxel/k-NN pooling, paired with flexible aggregations (SetTransformer, GraphMultisetTransformer, Set2Set, DeepSets, LSTMAggregation).
* **5 Pre-Trained Foundation Models:** Complete weight-converter pipelines for pre-trained foundation models:
  * **GraphMAE2** (masked graph autoencoder)
  * **Graphormer** (2D & 3D molecular transformer)
  * **GraphGPS** (general powerful spatial/spectral architecture)
  * **GROVER** & **Mole-BERT** (molecular representation models)
* **Knowledge Graph Embeddings:** Implemented 5 KG embedding models (`TransE`, `RotatE`, `DistMult`, `ComplEx`, `KGTripletLoader`), 46 high-level models, and 26 mini-batch samplers (`NeighborLoader`, `ClusterLoader`, `GraphSAINTSampler`).
* **Rigorous Parity Testing:** Engineered **700+ unit tests per backend**, checking gradient flow, weight learning, and numerical parity against PyG reference checkpoints; authored 90+ Colab example notebooks.

