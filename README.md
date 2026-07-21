<div align="center">

# Abdullah Saeed

### AI/ML Engineer · Biomedical Engineering Graduate

Building practical, evaluated AI/ML systems across computer vision, retrieval, local agents, simulation, and biomedical sensing.

<sub>Computer vision · LLM systems · simulation · biomedical sensing · full-stack AI tools</sub>

[LinkedIn](https://linkedin.com/in/abdullahsaeedpage) · [Email](mailto:Abdullah627268@gmail.com) · [GitHub](https://github.com/Abp0101)

</div>

---

## About

I am a Biomedical Engineering graduate focused on applied AI, machine learning, and software engineering.

My strongest work is in **computer vision**, **retrieval-augmented generation**, **local agent systems**, **simulation-driven evaluation**, and **biomedical sensing**. I build projects with clear inputs, measurable outputs, and enough engineering detail for another developer to inspect, run, and extend.

I am currently seeking graduate AI/ML engineering and software engineering roles in London, with a particular interest in medical AI, local LLM systems, intelligent agents, and full-stack tools for technical users.

---

## Featured Projects

A curated selection of my strongest work, not a complete repository list. [Browse all public repositories](https://github.com/Abp0101?tab=repositories) for the rest of my projects and experiments.

### [RAGLab](https://github.com/Abp0101/raglab)

Multi-framework platform for implementing and fairly benchmarking retrieval-augmented generation pipelines across custom Python, LangChain, LangGraph, LlamaIndex, and Haystack. I built persistent ingestion, dense/BM25/hybrid retrieval, reranking, grounded generation with citation checks, a typed FastAPI service, deterministic evaluation, and a Next.js evidence workbench.

**Tech:** Python · FastAPI · Next.js · PostgreSQL · Qdrant · Redis · Ollama · LangChain · LangGraph · LlamaIndex · Haystack

**Result:** End-to-end local RAG platform with five executable pipelines, reproducible cross-framework reports, strict quality gates, and a zero-paid-API default path.

### [Chest X-Ray AI](https://github.com/Abp0101/chest-xray-ai)

Multi-label medical imaging classifier for thoracic disease detection on NIH ChestX-ray14. I built the full training and evaluation pipeline: patient-level splitting to reduce leakage risk, DenseNet-121 fine-tuning, class imbalance handling, AUC-ROC evaluation, and Grad-CAM model inspection.

**Tech:** PyTorch · DenseNet-121 · NIH ChestX-ray14 · BCEWithLogitsLoss · AUC-ROC · Grad-CAM · Gradio

**Result:** **0.7851 mean AUC-ROC** across 14 disease labels on the NIH test split.

<img src="https://raw.githubusercontent.com/Abp0101/chest-xray-ai/main/outputs/figures/gradcam_1_00018253_087.png" alt="Chest X-Ray AI Grad-CAM example" width="720">

<br>

### [MiniGPT](https://github.com/Abp0101/mini-gpt)

Small decoder-only transformer built from scratch to demonstrate how GPT-style language models work internally. I implemented causal self-attention, multi-head attention, fused QKV projection, GPT weight tying, checkpointing, generation controls, and a Streamlit interface.

**Tech:** PyTorch · decoder-only transformer · causal attention · fused QKV · weight tying · Streamlit

**Result:** Validation loss improved from **4.2369** to **1.6748** over a 3,000-step Tiny Shakespeare training run.

<img src="https://raw.githubusercontent.com/Abp0101/mini-gpt/main/assets/loss_curve.png" alt="MiniGPT training and validation loss curve" width="620">

<br>

### [FlowLLM](https://github.com/Abp0101/FlowLLM)

Traffic signal optimisation prototype that tests whether a local LLM can make useful phase-switching decisions from live simulation state. I built the SUMO intersection, TraCI controller loop, local Llama 3.1 decision layer through Ollama, and fixed-cycle baseline comparison.

**Tech:** Python · SUMO · TraCI · Ollama · Llama 3.1 · Streamlit · Pandas

**Result:** In the current saved 600-step simulation configuration, the prototype produced **14% lower average wait time** than the fixed-cycle baseline. This is a prototype result, not a real-world traffic claim.

### [CommandBar](https://github.com/Abp0101/CommandBar)

Local-first macOS AI command bar that answers questions and executes bounded native actions. I built intent classification, multi-step planning, human confirmation, formal execution-state tracking, saved workflows, and native tool handlers controlled by deterministic Swift code.

**Tech:** Swift · SwiftUI · AppKit · Ollama · AppleScript · local LLMs · human-in-the-loop agents

**Result:** Working macOS prototype with streamed answers, bounded tool execution, confirmation for generated plans, and reusable workflows.

### SmartKnee — Private academic project

Wearable rehabilitation monitoring prototype for tracking knee load and motion during recovery exercises. I built the sensor concept around FSR pressure readings, IMU motion data, signal processing, sensor fusion, Arduino firmware, Kotlin/mobile interaction, and real-time feedback states.

**Tech:** Arduino · FSR pressure sensors · MPU6050 IMU · signal processing · sensor fusion · Kotlin · Bluetooth LE

**Result:** Final-year biomedical capstone integrating pressure, motion, accessible multimodal feedback, and session-logging concepts for knee rehabilitation monitoring. The academic repository remains private, so this entry is intentionally not linked.

---

## Technical Focus

- **Machine learning:** PyTorch, computer vision, model evaluation, class imbalance handling, AUC-ROC, interpretability.
- **RAG and LLM systems:** multi-framework retrieval, dense/sparse/hybrid search, reranking, citation validation, local LLMs, structured outputs, and agent workflows.
- **Software engineering:** Python, Swift, C#, JavaScript/TypeScript, FastAPI, React, Next.js, Streamlit, .NET 8, and WinUI 3.
- **Simulation and data:** SUMO, TraCI, experiment baselines, metric-driven comparison, signal processing.
- **Biomedical technology:** wearable sensing, FSR sensors, IMU data, Arduino, Kotlin mobile workflows, sensor fusion.

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Abp0101&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=E6EDF3&text_color=CBD5E1&icon_color=8B949E)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Abp0101&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=E6EDF3&text_color=CBD5E1)

</div>

---

<div align="center">

Building practical AI systems with clean engineering, clear evaluation, and real-world intent.

</div>
