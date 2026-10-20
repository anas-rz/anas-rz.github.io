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
    <p class="mb-1 font-weight-bold" style="font-size: 0.95rem;">Rochester, MI</p>
    <p class="text-muted small mb-2">Oakland University</p>
    <div style="margin-top: 8px;">
      <span style="background: rgba(46, 204, 113, 0.12); color: #27ae60; border: 1px solid rgba(46, 204, 113, 0.3); padding: 4px 10px; border-radius: 9999px; font-size: 0.76rem; font-weight: 600; display: inline-block;">
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

<div class="bio-intro">
  <p class="lead" style="font-size: 1.15rem; line-height: 1.8; font-weight: 400; margin-bottom: 1rem;">
    I am a <strong>Ph.D. Candidate</strong> in Computer Science &amp; Informatics at <strong>Oakland University</strong>, specializing in <strong>Machine Learning Systems</strong>, <strong>Agentic AI</strong>, and <strong>Deep Learning Reliability</strong>.
  </p>
  <p style="font-size: 0.98rem; line-height: 1.75; font-weight: 400; color: var(--global-text-color);">
    My work bridges foundational deep learning with high-performance systems engineering—from zero-dependency C++/ggml inference engines and multi-backend ML libraries to autonomous multi-agent code generation and multimodal computer vision forensics.
  </p>
  <p style="font-size: 0.95rem; line-height: 1.7; font-weight: 400; color: var(--global-text-color-light);">
    I am an active open-source contributor to core <strong>Keras 3</strong> (20+ merged PRs) and author of <a href="/projects/" class="font-weight-bold text-decoration-none">timm.cpp</a> (C++ inference engine for 106 vision models), <a href="https://github.com/anas-rz/k3-node" target="_blank" rel="noopener noreferrer" class="font-weight-bold text-decoration-none">K3Node</a> (multi-backend GNNs with 100% PyG parity), and <a href="https://github.com/anas-rz/keras-climate" target="_blank" rel="noopener noreferrer" class="font-weight-bold text-decoration-none">Keras-Climate</a>.
  </p>
</div>

<!-- Clear the profile float so full-width sections render with perfect alignment -->
<div style="clear: both; margin-top: 1.5rem;"></div>

<!-- Interactive Three.js Neural / Systems Network Canvas -->
<div id="three-neural-card" class="rounded overflow-hidden mb-4" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color); box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);">
  <div class="d-flex justify-content-between align-items-center px-3 py-2" style="border-bottom: 1px solid var(--global-divider-color); background: var(--global-code-bg-color); font-size: 0.76rem; font-weight: 600; letter-spacing: 0.6px; text-transform: uppercase;">
    <span style="color: var(--global-theme-color);">
      <i class="fa-solid fa-network-wired mr-1"></i> Interactive Neural &amp; Systems Topology
    </span>
    <span class="text-muted font-weight-normal" style="font-size: 0.72rem;">
      <i class="fa-solid fa-hand-pointer mr-1"></i> Move cursor to tilt &bull; Click to pulse
    </span>
  </div>
  <div id="three-neural-container" style="position: relative; width: 100%; height: 210px; cursor: crosshair; background: radial-gradient(circle at 50% 50%, var(--global-code-bg-color) 0%, transparent 85%);">
    <canvas id="three-neural-canvas" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; display: block;"></canvas>
  </div>
</div>

<!-- Minimalist Interactive Impact Metrics -->
<div class="row text-center mb-4 g-2" style="margin-top: 1rem; margin-bottom: 2.2rem;">
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded metric-card" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div class="counter-value" data-target="12" style="font-size: 1.85rem; font-weight: 700; color: var(--global-theme-color);">0</div>
      <div class="text-muted small" style="font-size: 0.78rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; margin-top: 2px;">Papers (7 First-Author)</div>
    </div>
  </div>
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded metric-card" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div class="counter-value" data-target="237" data-suffix="+" style="font-size: 1.85rem; font-weight: 700; color: var(--global-theme-color);">0+</div>
      <div class="text-muted small" style="font-size: 0.78rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; margin-top: 2px;">Citations (h-index: 5)</div>
    </div>
  </div>
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded metric-card" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div class="counter-value" data-target="20" data-suffix="+" style="font-size: 1.85rem; font-weight: 700; color: var(--global-theme-color);">0+</div>
      <div class="text-muted small" style="font-size: 0.78rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; margin-top: 2px;">Merged PRs to Keras 3</div>
    </div>
  </div>
  <div class="col-6 col-md-3 mb-2">
    <div class="p-3 rounded metric-card" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div class="counter-value" data-target="106" style="font-size: 1.85rem; font-weight: 700; color: var(--global-theme-color);">0</div>
      <div class="text-muted small" style="font-size: 0.78rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; margin-top: 2px;">C++/ggml Vision Models</div>
    </div>
  </div>
</div>

<hr style="border-top: 1px solid var(--global-divider-color); margin: 2rem 0;">

### Research &amp; Engineering Focus

<div class="focus-pillars mb-4">
  <div class="pillar-item mb-3">
    <h5 style="font-weight: 600; font-size: 1.05rem; margin-bottom: 0.35rem;">
      <i class="fa-solid fa-microchip mr-2" style="color: var(--global-theme-color);"></i>High-Performance ML Systems &amp; Inference
    </h5>
    <p style="font-size: 0.94rem; line-height: 1.7; color: var(--global-text-color); margin-bottom: 0;">
      Leading development of <strong><a href="/projects/">timm.cpp</a></strong>, a standalone C++17 inference engine executing 106 PyTorch/timm architectures via GGUF and ggml with zero Python runtime dependency. Achieved up to <strong>25.8× faster cold-start load times</strong> via zero-copy POSIX <code>mmap</code> and <strong>3.4×–5.8× calibrated quantization</strong> weight compression.
    </p>
  </div>

  <div class="pillar-item mb-3">
    <h5 style="font-weight: 600; font-size: 1.05rem; margin-bottom: 0.35rem;">
      <i class="fa-solid fa-cubes mr-2" style="color: var(--global-theme-color);"></i>Multi-Backend Frameworks &amp; Open Source
    </h5>
    <p style="font-size: 0.94rem; line-height: 1.7; color: var(--global-text-color); margin-bottom: 0;">
      Core contributor to Keras 3 with 20+ merged pull requests. Author of <strong><a href="https://github.com/anas-rz/k3-node" target="_blank" rel="noopener noreferrer">K3Node</a></strong> (multi-backend Graph Neural Network library achieving 100% PyG API parity with 700+ tests/backend), <strong><a href="https://github.com/anas-rz/k3im" target="_blank" rel="noopener noreferrer">K3IM</a></strong> (50+ vision &amp; spatiotemporal architectures in 1D, 2D, and 3D), and <strong><a href="https://github.com/anas-rz/keras-climate" target="_blank" rel="noopener noreferrer">Keras-Climate</a></strong> (Earth observation and weather forecasting).
    </p>
  </div>

  <div class="pillar-item mb-3">
    <h5 style="font-weight: 600; font-size: 1.05rem; margin-bottom: 0.35rem;">
      <i class="fa-solid fa-robot mr-2" style="color: var(--global-theme-color);"></i>Agentic AI &amp; Neural Architecture Search
    </h5>
    <p style="font-size: 0.94rem; line-height: 1.7; color: var(--global-text-color); margin-bottom: 0;">
      Designed <strong>AutoMAS</strong> (IEEE QRS 2026), an autonomous framework automating the generation of functional multi-agent systems across 5 cooperative layers, achieving 82.75% Pass@1. Author of <strong>NeuroGenesis</strong> (IEEE QRS 2026), introducing reasoning-guided multimodal architecture search using LLMs across audio, video, images, and time series.
    </p>
  </div>

  <div class="pillar-item mb-3">
    <h5 style="font-weight: 600; font-size: 1.05rem; margin-bottom: 0.35rem;">
      <i class="fa-solid fa-shield-halved mr-2" style="color: var(--global-theme-color);"></i>DL Reliability, Forensics &amp; AIOps
    </h5>
    <p style="font-size: 0.94rem; line-height: 1.7; color: var(--global-text-color); margin-bottom: 0;">
      Developed <strong>LocatorGraph</strong> (<em>Empirical Software Engineering</em>, 2025) for GNN-based fault localization on sequence model computation graphs; created award-winning deepfake forensic architectures (<strong>RuleBoost</strong>, Best Poster Award at IEEE IJCB 2024; <strong>Multimodaltrace</strong>, CVPRW 2023 with 129+ citations); and developed <strong>DeepTrAnS</strong> (IEEE ICSC 2025) for unsupervised server telemetry anomaly detection (99.88% precision).
    </p>
  </div>
</div>

<hr style="border-top: 1px solid var(--global-divider-color); margin: 2rem 0;">

### Technical Expertise &amp; Skills

<!-- Interactive Skill Filter Bar -->
<div class="skills-filter-bar mb-3" style="display: flex; flex-wrap: wrap; gap: 6px; margin-top: 0.5rem;">
  <button type="button" class="skill-filter-btn active" data-category="all">All Skills</button>
  <button type="button" class="skill-filter-btn" data-category="languages">Languages</button>
  <button type="button" class="skill-filter-btn" data-category="deep-learning">Deep Learning</button>
  <button type="button" class="skill-filter-btn" data-category="ml-systems">ML Systems</button>
  <button type="button" class="skill-filter-btn" data-category="cloud">Cloud &amp; Infra</button>
  <button type="button" class="skill-filter-btn" data-category="fullstack">Full-Stack</button>
</div>

<div class="skills-section mt-3 mb-4">
  <div class="skill-group mb-3" data-category="languages">
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

  <div class="skill-group mb-3" data-category="deep-learning">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-brain mr-1"></i> Deep Learning &amp; Frameworks
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
      <span class="skill-tag">NumPy &amp; pandas</span>
    </div>
  </div>

  <div class="skill-group mb-3" data-category="ml-systems">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-microchip mr-1"></i> ML Systems &amp; Inference Engineering
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">ggml &amp; GGUF</span>
      <span class="skill-tag">llama.cpp / llama-server</span>
      <span class="skill-tag">Zero-Copy POSIX mmap</span>
      <span class="skill-tag">Calibrated Quantization (Q8_0, Q4_0, Q4_K)</span>
      <span class="skill-tag">Weight Porting Pipelines</span>
      <span class="skill-tag">Numerical Parity Testing</span>
      <span class="skill-tag">AVX-512 / ARM NEON SIMD</span>
    </div>
  </div>

  <div class="skill-group mb-3" data-category="cloud">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-cloud mr-1"></i> Cloud, MLOps &amp; Infrastructure
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">AWS (S3, EC2, Lambda, SageMaker, VPC, IAM, EKS)</span>
      <span class="skill-tag">Docker &amp; Docker Compose</span>
      <span class="skill-tag">Kubernetes (kubeadm, kubectl, AKS, GKE)</span>
      <span class="skill-tag">Terraform (IaC)</span>
      <span class="skill-tag">HPC / SLURM</span>
      <span class="skill-tag">Tesla V100 Clusters</span>
      <span class="skill-tag">NVIDIA Jetson Edge</span>
      <span class="skill-tag">InfluxDB &amp; Grafana</span>
    </div>
  </div>

  <div class="skill-group mb-3" data-category="fullstack">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-layer-group mr-1"></i> Full-Stack &amp; Platforms
    </div>
    <div style="line-height: 2.2;">
      <span class="skill-tag">React 19 &amp; Vite</span>
      <span class="skill-tag">React Native &amp; Expo SDK 53</span>
      <span class="skill-tag">Flutter &amp; Dart</span>
      <span class="skill-tag">Node.js &amp; Express</span>
      <span class="skill-tag">Apollo Server &amp; Client</span>
      <span class="skill-tag">GraphQL Subscriptions (WebSockets)</span>
      <span class="skill-tag">MongoDB &amp; Aggregations</span>
      <span class="skill-tag">Tailwind CSS v4</span>
    </div>
  </div>
</div>

<hr style="border-top: 1px solid var(--global-divider-color); margin: 2rem 0;">

### Featured Systems &amp; Research

<div class="row g-3 mb-4">
  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">timm.cpp</h5>
        <span class="project-tag">C++17 / ggml</span>
      </div>
      <p class="small text-muted mb-2">High-performance inference engine for 106 vision architectures via GGUF with zero Python runtime dependency, 25.8× faster cold start, and calibrated quantization.</p>
      <a href="/projects/" class="small font-weight-bold">View System Details →</a>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">K3Node</h5>
        <span class="project-tag">Keras 3 / PyG</span>
      </div>
      <p class="small text-muted mb-2">Multi-backend Graph Neural Network library achieving 100% public API parity with PyTorch Geometric across PyTorch, TensorFlow, and JAX with 700+ tests/backend.</p>
      <a href="https://github.com/anas-rz/k3-node" target="_blank" rel="noopener noreferrer" class="small font-weight-bold">Explore on GitHub →</a>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">AutoMAS</h5>
        <span class="project-tag">IEEE QRS 2026</span>
      </div>
      <p class="small text-muted mb-2">Autonomous multi-agent system generator translating natural language code intent into working agent systems across 5 cooperative layers (82.75% Pass@1).</p>
      <a href="/projects/" class="small font-weight-bold">View Research Details →</a>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-baseline mb-1">
        <h5 class="font-weight-bold mb-0">RuleBoost</h5>
        <span class="project-tag">IJCB '24 Best Poster</span>
      </div>
      <p class="small text-muted mb-2">Neuro-symbolic deepfake detector fusing geometric facial rules with deep representations (96.19% AUC on WLDR), recipient of the Best Poster Award at IEEE IJCB 2024.</p>
      <a href="/projects/" class="small font-weight-bold">View Publication →</a>
    </div>
  </div>
</div>

<hr style="border-top: 1px solid var(--global-divider-color); margin: 2rem 0;">

### Recent News &amp; Updates

* **2026:** Two research papers accepted at **IEEE QRS 2026**: *AutoMAS* (End-to-End Generation of Functional Multi-Agent Systems) and *NeuroGenesis* (LLM-Driven Neural Architecture Search).
* **2026:** Released **[Keras-Climate](https://anas-rz.github.io/keras-climate)**, a multi-backend framework for Earth Observation and Climate Modeling.
* **2025:** Published *Graph Neural Network for Fault Localization in Sequence-Based Models* (**LocatorGraph**) in **Empirical Software Engineering (EMSE)**.
* **2025:** Published *DeepTrAnS: Mixer-based Unsupervised Time Series Anomaly Detection for Servers* in **IEEE ICSC 2025**.
* **2024:** Received the **Best Poster Award** at **IEEE IJCB 2024** for *RuleBoost: A Neuro-Symbolic Framework for Robust Deepfake Detection*.

<style>
  /* Montserrat universal font application */
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,400;1,600&display=swap');

  body,
  h1, h2, h3, h4, h5, h6,
  .post-title, .desc, p, .lead,
  .navbar, .navbar a, .nav-link,
  .card-title, .card-text,
  .badge, .counter-value, .project-tag, .skill-tag, .skill-filter-btn, .project-filter-pill,
  button, a {
    font-family: 'Montserrat', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif !important;
  }

  .metric-card {
    transition: transform 0.25s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0.25s ease, border-color 0.25s ease;
  }
  .metric-card:hover {
    transform: translateY(-3px);
    border-color: var(--global-theme-color) !important;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
  }
  .system-feature-card {
    transition: transform 0.25s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0.25s ease, border-color 0.25s ease;
  }
  .system-feature-card:hover {
    transform: translateY(-4px);
    border-color: var(--global-theme-color) !important;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
  }
  .skill-filter-btn {
    padding: 5px 14px;
    font-size: 0.8rem;
    font-weight: 500;
    border-radius: 9999px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-text-color);
    cursor: pointer;
    transition: all 0.2s ease;
    outline: none;
  }
  .skill-filter-btn:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color);
  }
  .skill-filter-btn.active {
    background: var(--global-theme-color);
    color: #ffffff !important;
    border-color: var(--global-theme-color);
  }
  .skill-tag {
    display: inline-block;
    padding: 4px 12px;
    margin: 3px 2px;
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
    transform: translateY(-1px);
  }
  .project-tag {
    display: inline-block;
    padding: 3px 9px;
    font-size: 0.72rem;
    font-weight: 600;
    border-radius: 4px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-theme-color);
  }
  .skill-group {
    transition: opacity 0.25s ease, transform 0.25s ease;
  }
  .pillar-item {
    padding: 12px 16px;
    border-radius: 8px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-card-bg-color);
    transition: border-color 0.2s ease, transform 0.2s ease;
  }
  .pillar-item:hover {
    border-color: var(--global-theme-color);
    transform: translateX(4px);
  }
</style>

<!-- Three.js CDN -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>

<script>
  (function () {
    'use strict';

    // 1. THREE.JS TOPOLOGY VISUALIZER
    function initThreeNeuralCanvas() {
      const card = document.getElementById('three-neural-card');
      const container = document.getElementById('three-neural-container');
      const canvas = document.getElementById('three-neural-canvas');
      if (!container || !canvas || typeof THREE === 'undefined') return;

      let width = container.clientWidth || 700;
      let height = container.clientHeight || 210;
      let isVisible = true;
      let mouseX = 0, mouseY = 0, targetX = 0, targetY = 0;
      let pulseWave = 0, isPulsing = false;
      const nodeCount = 50;
      const maxDistance = 64;

      function getColors() {
        const isDark = document.documentElement.getAttribute('data-theme') === 'dark';
        return {
          isDark: isDark,
          nodeColor: isDark ? 0x00e5ff : 0x4f46e5,
          lineColor: isDark ? 0x22d3ee : 0x6366f1,
          lineOpacity: isDark ? 0.32 : 0.20,
          nodeSize: isDark ? 3.8 : 3.2
        };
      }

      let colors = getColors();

      const scene = new THREE.Scene();
      const camera = new THREE.PerspectiveCamera(50, width / height, 1, 1000);
      camera.position.z = 130;

      let renderer;
      try {
        renderer = new THREE.WebGLRenderer({
          canvas: canvas,
          alpha: true,
          antialias: true,
          powerPreference: 'high-performance'
        });
        renderer.setPixelRatio(Math.min(window.devicePixelRatio || 1, 2));
        renderer.setSize(width, height, false);
      } catch (e) {
        console.warn('WebGL init error:', e);
        return;
      }

      const particlePositions = new Float32Array(nodeCount * 3);
      const particleVelocities = [];

      for (let i = 0; i < nodeCount; i++) {
        const x = (Math.random() - 0.5) * 160;
        const y = (Math.random() - 0.5) * 85;
        const z = (Math.random() - 0.5) * 60;
        particlePositions[i * 3] = x;
        particlePositions[i * 3 + 1] = y;
        particlePositions[i * 3 + 2] = z;
        particleVelocities.push({
          x: (Math.random() - 0.5) * 0.20,
          y: (Math.random() - 0.5) * 0.20,
          z: (Math.random() - 0.5) * 0.14
        });
      }

      const particlesGeo = new THREE.BufferGeometry();
      particlesGeo.setAttribute('position', new THREE.BufferAttribute(particlePositions, 3));
      const pMaterial = new THREE.PointsMaterial({
        color: colors.nodeColor,
        size: colors.nodeSize,
        transparent: true,
        opacity: 0.9,
        blending: THREE.AdditiveBlending
      });
      const nodesMesh = new THREE.Points(particlesGeo, pMaterial);
      scene.add(nodesMesh);

      const segments = nodeCount * nodeCount;
      const linePositions = new Float32Array(segments * 3);
      const lineColors = new Float32Array(segments * 3);
      const linesGeo = new THREE.BufferGeometry();
      linesGeo.setAttribute('position', new THREE.BufferAttribute(linePositions, 3).setUsage(THREE.DynamicDrawUsage));
      linesGeo.setAttribute('color', new THREE.BufferAttribute(lineColors, 3).setUsage(THREE.DynamicDrawUsage));

      const lineMaterial = new THREE.LineSegments(
        linesGeo,
        new THREE.LineBasicMaterial({
          vertexColors: true,
          transparent: true,
          opacity: colors.lineOpacity,
          blending: THREE.AdditiveBlending
        })
      );
      scene.add(lineMaterial);

      container.addEventListener('pointermove', (e) => {
        const rect = container.getBoundingClientRect();
        targetX = (((e.clientX - rect.left) / width) * 2 - 1) * 18;
        targetY = -(((e.clientY - rect.top) / height) * 2 - 1) * 14;
      }, { passive: true });

      container.addEventListener('pointerleave', () => { targetX = 0; targetY = 0; });
      container.addEventListener('click', () => { pulseWave = 1.0; isPulsing = true; });

      // Clean resize with ResizeObserver
      if (window.ResizeObserver) {
        const ro = new ResizeObserver(() => {
          width = container.clientWidth || 700;
          height = container.clientHeight || 210;
          camera.aspect = width / height;
          camera.updateProjectionMatrix();
          renderer.setSize(width, height, false);
        });
        ro.observe(container);
      } else {
        window.addEventListener('resize', () => {
          width = container.clientWidth || 700;
          height = container.clientHeight || 210;
          camera.aspect = width / height;
          camera.updateProjectionMatrix();
          renderer.setSize(width, height, false);
        });
      }

      const themeObserver = new MutationObserver(() => {
        colors = getColors();
        pMaterial.color.setHex(colors.nodeColor);
        pMaterial.size = colors.nodeSize;
        lineMaterial.material.opacity = colors.lineOpacity;
      });
      themeObserver.observe(document.documentElement, { attributes: true, attributeFilter: ['data-theme'] });

      const visObserver = new IntersectionObserver((entries) => {
        entries.forEach(entry => { isVisible = entry.isIntersecting; });
      }, { threshold: 0.05 });
      visObserver.observe(container);

      function animate() {
        requestAnimationFrame(animate);
        if (!isVisible) return;

        mouseX += (targetX - mouseX) * 0.05;
        mouseY += (targetY - mouseY) * 0.05;
        camera.position.x = mouseX;
        camera.position.y = mouseY;
        camera.lookAt(scene.position);

        if (isPulsing) {
          pulseWave *= 0.94;
          if (pulseWave < 0.01) { pulseWave = 0; isPulsing = false; }
        }

        let lineIdx = 0;
        const baseR = ((colors.lineColor >> 16) & 255) / 255;
        const baseG = ((colors.lineColor >> 8) & 255) / 255;
        const baseB = (colors.lineColor & 255) / 255;

        for (let i = 0; i < nodeCount; i++) {
          const i3 = i * 3;
          const vel = particleVelocities[i];
          particlePositions[i3] += vel.x;
          particlePositions[i3 + 1] += vel.y;
          particlePositions[i3 + 2] += vel.z;

          if (particlePositions[i3] < -85 || particlePositions[i3] > 85) vel.x = -vel.x;
          if (particlePositions[i3 + 1] < -42 || particlePositions[i3 + 1] > 42) vel.y = -vel.y;
          if (particlePositions[i3 + 2] < -35 || particlePositions[i3 + 2] > 35) vel.z = -vel.z;

          if (isPulsing) {
            particlePositions[i3] += (particlePositions[i3] > 0 ? 1 : -1) * pulseWave * 0.2;
            particlePositions[i3 + 1] += (particlePositions[i3 + 1] > 0 ? 1 : -1) * pulseWave * 0.2;
          }

          for (let j = i + 1; j < nodeCount; j++) {
            const j3 = j * 3;
            const dx = particlePositions[i3] - particlePositions[j3];
            const dy = particlePositions[i3 + 1] - particlePositions[j3 + 1];
            const dz = particlePositions[i3 + 2] - particlePositions[j3 + 2];
            const dist = Math.sqrt(dx * dx + dy * dy + dz * dz);

            if (dist < maxDistance) {
              const alpha = 1.0 - dist / maxDistance;
              linePositions[lineIdx * 3] = particlePositions[i3];
              linePositions[lineIdx * 3 + 1] = particlePositions[i3 + 1];
              linePositions[lineIdx * 3 + 2] = particlePositions[i3 + 2];
              lineColors[lineIdx * 3] = baseR;
              lineColors[lineIdx * 3 + 1] = baseG;
              lineColors[lineIdx * 3 + 2] = baseB;
              lineIdx++;

              linePositions[lineIdx * 3] = particlePositions[j3];
              linePositions[lineIdx * 3 + 1] = particlePositions[j3 + 1];
              linePositions[lineIdx * 3 + 2] = particlePositions[j3 + 2];
              lineColors[lineIdx * 3] = baseR * alpha;
              lineColors[lineIdx * 3 + 1] = baseG * alpha;
              lineColors[lineIdx * 3 + 2] = baseB * alpha;
              lineIdx++;
            }
          }
        }

        nodesMesh.geometry.attributes.position.needsUpdate = true;
        linesGeo.setDrawRange(0, lineIdx);
        linesGeo.attributes.position.needsUpdate = true;
        linesGeo.attributes.color.needsUpdate = true;

        scene.rotation.y += 0.0012;
        renderer.render(scene, camera);
      }
      animate();
    }

    function checkThree() {
      if (typeof THREE !== 'undefined') {
        initThreeNeuralCanvas();
      } else {
        setTimeout(checkThree, 60);
      }
    }

    // 2. ANIMATED NUMERIC COUNTERS
    function initCounters() {
      const counters = document.querySelectorAll('.counter-value');
      if (!counters.length) return;

      const observer = new IntersectionObserver((entries, obs) => {
        entries.forEach(entry => {
          if (!entry.isIntersecting) return;
          const el = entry.target;
          const target = parseInt(el.getAttribute('data-target'), 10);
          const suffix = el.getAttribute('data-suffix') || '';
          const duration = 1200;
          const startTime = performance.now();

          function updateCounter(now) {
            const progress = Math.min((now - startTime) / duration, 1.0);
            const easeOut = 1 - Math.pow(1 - progress, 3);
            el.textContent = Math.floor(easeOut * target) + suffix;
            if (progress < 1.0) {
              requestAnimationFrame(updateCounter);
            } else {
              el.textContent = target + suffix;
            }
          }
          requestAnimationFrame(updateCounter);
          obs.unobserve(el);
        });
      }, { threshold: 0.15 });

      counters.forEach(c => observer.observe(c));
    }

    // 3. SKILL FILTER
    function initSkillFilter() {
      const buttons = document.querySelectorAll('.skill-filter-btn');
      const groups = document.querySelectorAll('.skill-group');
      if (!buttons.length || !groups.length) return;

      buttons.forEach(btn => {
        btn.addEventListener('click', function () {
          const category = this.getAttribute('data-category');
          buttons.forEach(b => b.classList.remove('active'));
          this.classList.add('active');

          groups.forEach(g => {
            if (category === 'all' || g.getAttribute('data-category') === category) {
              g.style.display = 'block';
              g.style.opacity = '1';
            } else {
              g.style.display = 'none';
            }
          });
        });
      });
    }

    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', () => {
        checkThree();
        initCounters();
        initSkillFilter();
      });
    } else {
      checkThree();
      initCounters();
      initSkillFilter();
    }
  })();
</script>
