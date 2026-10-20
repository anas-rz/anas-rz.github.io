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
      <span style="background: rgba(16, 185, 129, 0.1); color: #059669; border: 1px solid rgba(16, 185, 129, 0.25); padding: 4px 10px; border-radius: 9999px; font-size: 0.76rem; font-weight: 600; display: inline-block;">
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
    My work bridges foundational deep learning with high-performance systems engineering, spanning zero-dependency C++/ggml inference engines, multi-backend ML libraries, autonomous multi-agent code generation, and multimodal computer vision forensics.
  </p>
  <p style="font-size: 0.95rem; line-height: 1.7; font-weight: 400; color: var(--global-text-color-light);">
    I am an active open-source contributor to core <strong>Keras 3</strong> (20+ merged PRs) and author of <a href="/projects/" class="font-weight-bold text-decoration-none">timm.cpp</a> (C++ inference engine for 106 vision models), <a href="https://github.com/anas-rz/k3-node" target="_blank" rel="noopener noreferrer" class="font-weight-bold text-decoration-none">K3Node</a> (multi-backend GNNs with 100% PyG parity), and <a href="https://github.com/anas-rz/keras-climate" target="_blank" rel="noopener noreferrer" class="font-weight-bold text-decoration-none">Keras-Climate</a>.
  </p>
</div>

<!-- Clear the profile float so full-width sections render with perfect alignment -->
<div style="clear: both; margin-top: 1.5rem;"></div>

<!-- Minimalist Impact Metrics -->
<div class="row text-center mb-4 g-2 justify-content-center" style="margin-top: 1rem; margin-bottom: 2rem;">
  <div class="col-4 col-md-4 mb-2">
    <div class="p-3 rounded metric-card" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div style="font-size: 1.85rem; font-weight: 700; color: var(--global-theme-color);">12</div>
      <div class="text-muted small" style="font-size: 0.78rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; margin-top: 2px;">Papers (7 First-Author)</div>
    </div>
  </div>
  <div class="col-4 col-md-4 mb-2">
    <div class="p-3 rounded metric-card" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div style="font-size: 1.85rem; font-weight: 700; color: var(--global-theme-color);">237+</div>
      <div class="text-muted small" style="font-size: 0.78rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; margin-top: 2px;">Citations (h-index: 5)</div>
    </div>
  </div>
  <div class="col-4 col-md-4 mb-2">
    <div class="p-3 rounded metric-card" style="border: 1px solid var(--global-divider-color); background: var(--global-code-bg-color);">
      <div style="font-size: 1.85rem; font-weight: 700; color: var(--global-theme-color);">5+</div>
      <div class="text-muted small" style="font-size: 0.78rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px; margin-top: 2px;">Open-Source Projects</div>
    </div>
  </div>
</div>

<hr style="border-top: 1px solid var(--global-divider-color); margin: 2rem 0;">

<div class="d-flex justify-content-between align-items-baseline mb-3">
  <h3 id="featured-systems" style="font-weight: 700; margin-bottom: 0;">Featured Systems &amp; Research</h3>
  <a href="/projects/" class="small font-weight-bold" style="color: var(--global-theme-color); text-decoration: none;">View All 12 Projects →</a>
</div>

<div class="row g-3 mb-4">
  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-center mb-2">
        <h5 class="font-weight-bold mb-0" style="font-size: 1.05rem;">
          <i class="fa-solid fa-microchip mr-2" style="color: var(--global-theme-color);"></i>timm.cpp
        </h5>
        <span class="project-tag">C++17 / ggml</span>
      </div>
      <p class="small text-muted mb-2" style="line-height: 1.6;">
        Standalone inference engine executing 106 PyTorch/timm architectures via GGUF with zero Python runtime dependency. Achieved up to <strong>25.8× faster cold-start load times</strong> via zero-copy POSIX <code>mmap</code> and <strong>3.4× to 5.8× calibrated quantization</strong> weight compression.
      </p>
      <div class="mt-auto pt-2">
        <a href="/projects/" class="small font-weight-bold" style="color: var(--global-theme-color); text-decoration: none;">Explore System Architecture →</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-center mb-2">
        <h5 class="font-weight-bold mb-0" style="font-size: 1.05rem;">
          <i class="fa-solid fa-cubes mr-2" style="color: var(--global-theme-color);"></i>K3Node &amp; Keras 3
        </h5>
        <span class="project-tag">Core Contributor</span>
      </div>
      <p class="small text-muted mb-2" style="line-height: 1.6;">
        Core contributor to Keras 3 with 20+ merged PRs. Author of <strong>K3Node</strong> (multi-backend GNN library with 100% PyG parity across PyTorch, TensorFlow, and JAX with 700+ tests/backend), <strong>K3IM</strong> (50+ vision backbones), and <strong>Keras-Climate</strong>.
      </p>
      <div class="mt-auto pt-2">
        <a href="https://github.com/anas-rz/k3-node" target="_blank" rel="noopener noreferrer" class="small font-weight-bold" style="color: var(--global-theme-color); text-decoration: none;">View K3Node on GitHub →</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-center mb-2">
        <h5 class="font-weight-bold mb-0" style="font-size: 1.05rem;">
          <i class="fa-solid fa-robot mr-2" style="color: var(--global-theme-color);"></i>AutoMAS &amp; NeuroGenesis
        </h5>
        <span class="project-tag">IEEE QRS 2026</span>
      </div>
      <p class="small text-muted mb-2" style="line-height: 1.6;">
        Architected <strong>AutoMAS</strong>, an autonomous framework translating natural language code intent into working multi-agent systems across 5 cooperative layers (82.75% Pass@1). Authored <strong>NeuroGenesis</strong>, introducing reasoning-guided multimodal architecture search using LLMs.
      </p>
      <div class="mt-auto pt-2">
        <a href="/projects/" class="small font-weight-bold" style="color: var(--global-theme-color); text-decoration: none;">Read Agentic AI Papers →</a>
      </div>
    </div>
  </div>

  <div class="col-md-6 mb-3">
    <div class="p-3 rounded h-100 system-feature-card" style="border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color);">
      <div class="d-flex justify-content-between align-items-center mb-2">
        <h5 class="font-weight-bold mb-0" style="font-size: 1.05rem;">
          <i class="fa-solid fa-shield-halved mr-2" style="color: var(--global-theme-color);"></i>DL Reliability &amp; Forensics
        </h5>
        <span class="project-tag">Best Poster Award</span>
      </div>
      <p class="small text-muted mb-2" style="line-height: 1.6;">
        Authored <strong>RuleBoost</strong> (Best Poster Award at IEEE IJCB 2024; 96.19% AUC), <strong>LocatorGraph</strong> (<em>Empirical Software Engineering</em> 2025; GNN fault localization on DL computation graphs), and <strong>DeepTrAnS</strong> (IEEE ICSC 2025; 99.88% precision telemetry anomaly detection).
      </p>
      <div class="mt-auto pt-2">
        <a href="/projects/" class="small font-weight-bold" style="color: var(--global-theme-color); text-decoration: none;">View Forensic Architectures →</a>
      </div>
    </div>
  </div>
</div>

<hr style="border-top: 1px solid var(--global-divider-color); margin: 2rem 0;">

<div class="d-flex justify-content-between align-items-baseline mb-3">
  <h3 id="technical-skills" style="font-weight: 700; margin-bottom: 0;">Technical Expertise &amp; Skills</h3>
</div>

<div class="skills-section mt-3 mb-4">
  <div class="skill-group mb-3">
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

  <div class="skill-group mb-3">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-brain mr-1"></i> Deep Learning Frameworks
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

  <div class="skill-group mb-3">
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

  <div class="skill-group mb-3">
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

  <div class="skill-group mb-3">
    <div class="small text-uppercase font-weight-bold mb-1" style="color: var(--global-theme-color); letter-spacing: 0.5px;">
      <i class="fa-solid fa-layer-group mr-1"></i> Full-Stack Platforms
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

<div class="d-flex justify-content-between align-items-baseline mb-3">
  <h3 style="font-weight: 700; margin-bottom: 0;">Recent Milestones &amp; News</h3>
  <a href="/publications/" class="small font-weight-bold" style="color: var(--global-theme-color); text-decoration: none;">View All Publications →</a>
</div>

<ul class="milestones-list mb-4" style="padding-left: 1.2rem; font-size: 0.95rem; line-height: 1.8;">
  <li><strong>2026:</strong> Two research papers accepted at <strong>IEEE QRS 2026</strong>: <em>AutoMAS</em> (End-to-End Generation of Functional Multi-Agent Systems) and <em>NeuroGenesis</em> (LLM-Driven Neural Architecture Search).</li>
  <li><strong>2026:</strong> Released <strong><a href="https://anas-rz.github.io/keras-climate" target="_blank" rel="noopener noreferrer">Keras-Climate</a></strong>, a multi-backend framework for Earth Observation and Climate Modeling.</li>
  <li><strong>2025:</strong> Published <em>Graph Neural Network for Fault Localization in Sequence-Based Models</em> (<strong>LocatorGraph</strong>) in <strong>Empirical Software Engineering (EMSE)</strong>.</li>
  <li><strong>2025:</strong> Published <em>DeepTrAnS: Mixer-based Unsupervised Time Series Anomaly Detection for Servers</em> in <strong>IEEE ICSC 2025</strong>.</li>
  <li><strong>2024:</strong> Received the <strong>Best Poster Award</strong> at <strong>IEEE IJCB 2024</strong> for <em>RuleBoost: A Neuro-Symbolic Framework for Robust Deepfake Detection</em>.</li>
</ul>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,400;1,600&display=swap');

  body,
  h1, h2, h3, h4, h5, h6,
  .post-title, .desc, p, .lead,
  .navbar, .navbar a, .nav-link,
  .card-title, .card-text,
  .badge, .counter-value, .project-tag, .skill-tag,
  button, a {
    font-family: 'Montserrat', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif !important;
  }

  .metric-card {
    transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  }
  .metric-card:hover {
    transform: translateY(-2px);
    border-color: var(--global-theme-color) !important;
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.05);
  }
  .system-feature-card {
    transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
    display: flex;
    flex-direction: column;
  }
  .system-feature-card:hover {
    transform: translateY(-3px);
    border-color: var(--global-theme-color) !important;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
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
  }
  .project-tag {
    display: inline-block;
    padding: 3px 9px;
    font-size: 0.72rem;
    font-weight: 600;
    border-radius: 9999px;
    border: 1px solid var(--global-divider-color);
    background: var(--global-code-bg-color);
    color: var(--global-theme-color);
  }
</style>
