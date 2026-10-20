---
layout: page
title: "AutoMAS: Automated Multi-Agent System Generation"
description: "End-to-end framework generating functional multi-agent systems from natural language code intent across 5 cooperative agent layers (IEEE QRS 2026)."
importance: 1
category: "Research"
related_publications: true
---

# AutoMAS: Automated Multi-Agent System Generation

**Stack:** Python, LLM Agents, AST Parsing, Static/Dynamic Validation, Multi-Stage Testing  
**Venue:** IEEE International Conference on Software Quality, Reliability and Security (QRS 2026)  
**Authors:** Muhammad Anas Raza, Niful Islam, Mohammad Wardat

---

## Overview

**AutoMAS** is an end-to-end multi-agent framework designed to automate the construction of functional, deployable agentic software systems directly from high-level natural language intent. 

Rather than relying on single-shot LLM prompts, AutoMAS structures system design into **5 specialized cooperative layers**:
1. **Orchestrator Agent:** Deconstructs user intent into architectural specifications.
2. **Architect Agent:** Defines message protocols, state machines, and inter-agent topologies.
3. **Tool Agent:** Generates environment interfaces and tool bindings.
4. **Code Generation Agent:** Implements executable agent logic.
5. **Multi-Stage Tester Agent:** Executes automated syntax inspection, AST validation, runtime sandbox execution, and penalty-guided self-repair loops.

---

## Benchmark & Empirical Results

* **Curated Evaluation Benchmark:** Built a comprehensive benchmark of **91 real-world agentic systems** sourced from recent academic literature and production open-source repositories.
* **Literature Benchmark:** Achieved **82.75% Pass@1** and **89.78% system accuracy**, outperforming standard prompting strategies by over 28%.
* **GitHub Benchmark:** Achieved **72.58% Pass@1** and **82.43% accuracy** on complex multi-repository setups.
* Evaluated systematically across leading model backends including GPT-5.2, DeepSeek-v3.2, and Claude-Sonnet-4.6.

