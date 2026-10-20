---
layout: about
title: about
permalink: /
subtitle: Ph.D. Candidate & ML Systems / Research Engineer · Oakland University

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p class="mb-1 font-weight-bold">Rochester, MI</p>
    <p class="text-muted small mb-2">Oakland University</p>
    <div style="margin-top: 10px;">
      <span style="background: rgba(46, 204, 113, 0.12); color: #27ae60; border: 1px solid rgba(46, 204, 113, 0.3); padding: 4px 10px; border-radius: 9999px; font-size: 0.78rem; font-weight: 600; display: inline-block;">
        🟢 Open to ML Systems & Research Roles
      </span>
    </div>

selected_papers: true
social: true

announcements:
  enabled: false
latest_posts:
  enabled: false
---

<div class="intro-lead mb-4">
  <p class="lead" style="font-size: 1.15rem; line-height: 1.7; font-weight: 400;">
    I am a <strong>Ph.D. Candidate</strong> in Computer Science & Informatics at <strong>Oakland University</strong>, specializing in <strong>Machine Learning Systems</strong>, <strong>Agentic AI</strong>, and <strong>Deep Learning Reliability</strong>. My research and engineering work bridges foundational deep learning with production-grade systems—spanning zero-dependency C++/ggml inference engines, multi-backend ML frameworks, autonomous multi-agent code generation, and robust multimodal vision models.
  </p>
</div>

<!-- Minimalist Impact Metrics -->
<div class="row text-center mb-4 g-2" style="margin-top: 1.5rem; margin-bottom: 2rem;">
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div style="font-size: 1.6rem; font-weight: 700; color: var(--global-theme-color);">12</div>
      <div class="text-muted small" style="font-size: 0.82rem; font-weight: 500;">Papers (7 First-Author)</div>
    </div>
  </div>
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div style="font-size: 1.6rem; font-weight: 700; color: var(--global-theme-color);">230+</div>
      <div class="text-muted small" style="font-size: 0.82rem; font-weight: 500;">Citations (h-index: 5)</div>
    </div>
  </div>
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div style="font-size: 1.6rem; font-weight: 700; color: var(--global-theme-color);">20+</div>
      <div class="text-muted small" style="font-size: 0.82rem; font-weight: 500;">Merged PRs to Keras 3</div>
    </div>
  </div>
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div style="font-size: 1.6rem; font-weight: 700; color: var(--global-theme-color);">106</div>
      <div class="text-muted small" style="font-size: 0.82rem; font-weight: 500;">C++/ggml Vision Models</div>
    </div>
  </div>
</div>

---

### Research & Engineering Focus

* **High-Performance ML Systems & Inference:** Leading development of **[timm.cpp](/projects/)**, a standalone C++17 inference engine running 106 PyTorch/timm architectures via GGUF with zero Python runtime dependencies. Achieved up to **25.8× faster cold-start load times** via zero-copy POSIX `mmap` and **3.4×–5.8× calibrated quantization** weight compression.
* **Multi-Backend Frameworks & Open Source:** Core contributor to Keras 3 with 20+ merged pull requests. Author of **[K3Node](https://github.com/anas-rz/k3-node)** (multi-backend Graph Neural Network library achieving 100% PyG API parity with 700+ tests/backend), **[K3IM](https://github.com/anas-rz/k3im)** (50+ vision & spatiotemporal architectures in 1D, 2D, and 3D), and **[Keras-Climate](https://github.com/anas-rz/keras-climate)** (Earth observation and weather forecasting).
* **Agentic AI & Neural Architecture Search:** Designed **AutoMAS** (IEEE QRS 2026), an autonomous framework automating the generation of functional multi-agent systems across 5 cooperative layers, achieving 82.75% Pass@1. Author of **NeuroGenesis** (IEEE QRS 2026), introducing reasoning-guided multimodal architecture search using LLMs across audio, video, images, and time series.
* **DL Reliability, Forensics & AIOps:** Developed **LocatorGraph** (*Empirical Software Engineering*, 2025) for GNN-based fault localization on sequence model computation graphs; created award-winning deepfake forensic architectures (**RuleBoost**, Best Poster Award at IEEE IJCB 2024; **Multimodaltrace**, CVPRW 2023 with 129+ citations); and developed **DeepTrAnS** (IEEE ICSC 2025) for unsupervised server telemetry anomaly detection (99.88% precision).

---

### Technical Expertise & Skills

<div class="skills-section mt-3 mb-4">
  <div class="mb-3">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-code mr-1"></i> Programming Languages
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">Python</span>
      <span class="skill-tag">C++ / C++17</span>
      <span class="skill-tag">TypeScript</span>
      <span class="skill-tag">JavaScript (ES6+)</span>
      <span class="skill-tag">CUDA</span>
      <span class="skill-tag">Dart</span>
      <span class="skill-tag">Rust (basics)</span>
      <span class="skill-tag">Bash</span>
      <span class="skill-tag">SQL</span>
      <span class="skill-tag">LaTeX</span>
    </div>
  </div>

  <div class="mb-3">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-brain mr-1"></i> Deep Learning & Frameworks
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">PyTorch</span>
      <span class="skill-tag">Keras 3</span>
      <span class="skill-tag">TensorFlow</span>
      <span class="skill-tag">JAX</span>
      <span class="skill-tag">LibTorch</span>
      <span class="skill-tag">timm</span>
      <span class="skill-tag">Hugging Face</span>
      <span class="skill-tag">LangGraph</span>
      <span class="skill-tag">scikit-learn</span>
      <span class="skill-tag">NumPy & pandas</span>
    </div>
  </div>

  <div class="mb-3">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-microchip mr-1"></i> ML Systems & Inference Engineering
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">ggml & GGUF</span>
      <span class="skill-tag">llama.cpp / llama-server</span>
      <span class="skill-tag">Zero-Copy POSIX mmap</span>
      <span class="skill-tag">Calibrated Quantization (Q8_0, Q4_0, Q4_K)</span>
      <span class="skill-tag">Weight Porting Pipelines</span>
      <span class="skill-tag">Numerical Parity Testing</span>
      <span class="skill-tag">AVX-512 / ARM NEON SIMD</span>
    </div>
  </div>

  <div class="mb-3">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-cloud mr-1"></i> Cloud, MLOps & Infrastructure
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">AWS (S3, EC2, Lambda, SageMaker, VPC, IAM, EKS)</span>
      <span class="skill-tag">Docker & Docker Compose</span>
      <span class="skill-tag">Kubernetes (kubeadm, kubectl, AKS, GKE)</span>
      <span class="skill-tag">Terraform (IaC)</span>
      <span class="skill-tag">HPC / SLURM</span>
      <span class="skill-tag">Tesla V100 Clusters</span>
      <span class="skill-tag">NVIDIA Jetson Edge</span>
      <span class="skill-tag">InfluxDB & Grafana</span>
    </div>
  </div>

  <div>
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-layer-group mr-1"></i> Full-Stack & Platforms
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">React 19 & Vite</span>
      <span class="skill-tag">React Native & Expo SDK 53</span>
      <span class="skill-tag">Flutter & Dart</span>
      <span class="skill-tag">Node.js & Express</span>
      <span class="skill-tag">Apollo Server & Client</span>
      <span class="skill-tag">GraphQL Subscriptions (WebSockets)</span>
      <span class="skill-tag">MongoDB & Aggregations</span>
      <span class="skill-tag">Tailwind CSS v4</span>
    </div>
  </div>
</div>

<style>
  .skill-tag {
    display: inline-block;
    padding: 3px 11px;
    margin: 2px 2px;
    font-size: 0.84rem;
    font-weight: 500;
    border-radius: 9999px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-text-color);
    transition: all 0.15s ease-in-out;
  }
  .skill-tag:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color);
  }
  .project-tag {
    display: inline-block;
    padding: 2px 8px;
    font-size: 0.72rem;
    font-weight: 600;
    border-radius: 4px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-theme-color);
  }
</style>

---

### Featured Systems & Research

<div class="row g-3 mb-4">
  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">timm.cpp</h5>
        <span class="project-tag">C++17 / ggml</span>
      </div>
      <p class="small text-muted mb-2">High-performance inference engine for 106 vision architectures via GGUF with zero Python runtime dependency, 25.8× faster cold start, and calibrated quantization.</p>
      <a href="/projects/" class="small font-weight-bold">View System Details →</a>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">K3Node</h5>
        <span class="project-tag">Keras 3 / PyG</span>
      </div>
      <p class="small text-muted mb-2">Multi-backend Graph Neural Network library achieving 100% public API parity with PyTorch Geometric across PyTorch, TensorFlow, and JAX with 700+ tests/backend.</p>
      <a href="https://github.com/anas-rz/k3-node" target="_blank" rel="noopener noreferrer" class="small font-weight-bold">Explore on GitHub →</a>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">AutoMAS</h5>
        <span class="project-tag">IEEE QRS 2026</span>
      </div>
      <p class="small text-muted mb-2">Autonomous multi-agent system generator translating natural language code intent into working agent systems across 5 cooperative layers (82.75% Pass@1).</p>
      <a href="/projects/" class="small font-weight-bold">View Research Details →</a>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">RuleBoost</h5>
        <span class="project-tag">IJCB '24 Best Poster</span>
      </div>
      <p class="small text-muted mb-2">Neuro-symbolic deepfake detector fusing geometric facial rules with deep representations (96.19% AUC on WLDR), recipient of the Best Poster Award at IEEE IJCB 2024.</p>
      <a href="/projects/" class="small font-weight-bold">View Publication →</a>
    </div>
  </div>
</div>

---

### Recent News & Updates

* **2026:** Two research papers accepted at **IEEE QRS 2026**: *AutoMAS* (End-to-End Generation of Functional Multi-Agent Systems) and *NeuroGenesis* (LLM-Driven Neural Architecture Search).
* **2026:** Released **[Keras-Climate](https://anas-rz.github.io/keras-climate)**, a multi-backend framework for Earth Observation and Climate Modeling.
* **2025:** Published *Graph Neural Network for Fault Localization in Sequence-Based Models* (**LocatorGraph**) in **Empirical Software Engineering (EMSE)**.
* **2025:** Published *DeepTrAnS: Mixer-based Unsupervised Time Series Anomaly Detection for Servers* in **IEEE ICSC 2025**.
* **2024:** Received the **Best Poster Award** at **IEEE IJCB 2024** for *RuleBoost: A Neuro-Symbolic Framework for Robust Deepfake Detection*.
