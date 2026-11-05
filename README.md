# Deepan K S — AI Engineer Portfolio

Interactive single-page portfolio website showcasing production work across **Computer Vision**, **Agentic AI**, **Generative AI**, and **MLOps**.

- **Email:** [deepanks01@gmail.com](mailto:deepanks01@gmail.com)
- **Phone:** +91 82488 75443
- **LinkedIn:** [linkedin.com/in/deepan-ks](https://www.google.com/search?q=https://linkedin.com/in/deepan-ks)
- **GitHub:** [github.com/deepan2003](https://www.google.com/search?q=https://github.com/deepan2003)
- **Live Agentic RAG Demo:** [agentic-gateway.duckdns.org](https://www.google.com/search?q=https://agentic-gateway.duckdns.org)

## Overview

AI Engineer specializing in production Computer Vision, Agentic AI, and GenAI systems — building real-time multi-stream pipelines (`NVIDIA DeepStream`, `InsightFace`, `YOLOv8x`, `FAISS`), `LangGraph` multi-agent RAG with dual-layer LLM guardrails, and GPU-optimized inference with automated `AWS EC2` / `DVC` MLOps pipelines.

## Portfolio Features

- **Interactive Telemetry HUD:** Displays verified engineering metrics including `0.994` ROC-AUC (`98.1%` test accuracy), `100%` token savings on MD5 prompt cache hits, `24/7` DeepStream pipeline reliability, and `94%` OpenCV University certification grade.
- **30-Second Recruiter Mode:** Quick-view executive summary modal highlighting core production experience, architectures, and direct contact links.
- **System Architecture Blueprints:** Interactive modal diagrams for the Production Agentic RAG system, FastMCP Database Agent, and DVC/GitHub Actions MLOps pipeline.
- **Interactive Skills Radar & Production Evidence Matrix:** Filterable domain skills (`Computer Vision`, `Agentic AI`, `Generative AI`, `AI/ML Frameworks`, `MLOps & Infra`) mapped directly to real-world internship and project implementations.
- **Ask My AI Twin Assistant:** Built-in interactive first-person chat widget grounded on official CV data to answer recruiter questions about experience, tech stack, and availability.
- **Self-Contained Official CV Download:** Instant in-browser PDF download (`K S Deepan CV.pdf`) and high-contrast Dark/Light theme toggle.

## Production Experience

| Role | Organization | Location | Duration | Key Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **Artificial Intelligence Intern** | Bhatiyani Astute Intelligence Pvt. Ltd | Bangalore | Nov 2025 – Jun 2026 | Built a real-time multi-camera attendance pipeline on NVIDIA DeepStream (`nvinfer` + `nvtracker`) with InsightFace ArcFace and dual-index FAISS recognition microservice via FastAPI, MongoDB, and RabbitMQ; implemented entry/exit line-crossing counters, proximity/dwell detection, unattended-customer alerts, and 24/7 automatic pipeline recovery. |
| **Artificial Intelligence Intern** | Resilience Business Grids (RBG.AI) | Coimbatore | Jul 2025 – Nov 2025 | Developed a multi-modal security pipeline with custom YOLOv8x (11 bag classes), ViT-based gender classification, and anomaly detection (Abandoned Bag, Isolated People, Help Gesture) via MediaPipe + Deep SORT with Optical Flow camera stabilization. |

## Featured Projects

### 1. Production Agentic RAG System — LLM Gateway, Guardrails & Multi-Agent Orchestration
- **Links:** [Live Demo](https://www.google.com/search?q=https://agentic-gateway.duckdns.org) | [GitHub Repository](https://www.google.com/search?q=https://github.com/deepan2003/Agentic-AI)
- Deployed full-stack multi-agent RAG on AWS EC2 with a Streamlit frontend, Flask REST API, and LangGraph orchestration (`CHITCHAT` / `RESEARCH` / `SAVE_HISTORY`) with persistent `MemorySaver`.
- Built `SmartLLMGateway` with complexity-based routing to Groq (`Llama-3.1-8b` / `Llama-3.3-70b`), automatic Gemini fallback, MD5 prompt caching (`100%` token savings on hits), and load-balanced API key rotation with per-query cost tracking.
- Implemented dual-layer guardrails (regex + LLM cognitive prompt injection detection) and output hallucination verification against a Pydantic `FactSheet`, evaluated via LangSmith across 4 LLM-as-judge metrics.

### 2. Company Database AI Manager — Natural Language MCP Database Agent
- **Link:** [GitHub Repository](https://www.google.com/search?q=https://github.com/deepan2003/Database-MCP)
- Built a natural-language interface to a corporate SQLite database via Streamlit, enabling plain-English record insertion, updates, and queries without writing SQL.
- Architected a true Server/Client system using the Model Context Protocol (`FastMCP`) over `stdio` (`setup_database`, `add_record`, `search_database`), decoupling database logic from AI reasoning.
- Implemented a LangGraph agent powered by Groq (`llama-3.3-70b-versatile` / `openai/gpt-oss-120b`) over SQLAlchemy relational schemas (`Departments`, `Roles`, `Employees`, `Projects`).

### 3. MLOps Heart Attack Prediction Pipeline
- **Link:** [GitHub Repository](https://www.google.com/search?q=https://github.com/deepan2003/MLOPS)
- Automated reproducible ML pipeline with DVC (`preprocess → train → evaluate`), optimizing a `RandomForestClassifier` to achieve `98.1%` test accuracy and `0.994` ROC-AUC with hyperparameters tracked in `params.yaml`.
- Deployed to AWS EC2 via GitHub Actions CI/CD (`test → lint → rsync → Gunicorn restart`) and served through a production Flask REST API with zero manual steps post-commit.

## Technical Skills

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python |
| **AI/ML Frameworks** | PyTorch, TensorFlow/Keras, Scikit-learn, Hugging Face Transformers |
| **Computer Vision** | NVIDIA DeepStream, InsightFace, YOLOv8, OpenCV, FAISS, RetinaFace, ONNX |
| **Agentic AI** | LangGraph, LangChain, ReAct Agents, RAG Pipelines, LLM Guardrails, LangSmith, Model Context Protocol (FastMCP) |
| **Generative AI** | Groq API, Gemini API, Tavily Search, SentenceTransformers, FLAN-T5 |
| **MLOps & Infra** | Docker, FastAPI, Flask, DVC, GitHub Actions, AWS EC2, AWS S3 |

## Education & Certifications

- **Integrated M.Sc. Data Science** — Amrita Vishwa Vidyapeetham (Aug 2021 – Apr 2026)
  - *Research:* LSTM-based AI for cloud infrastructure resiliency using Sierpinski Graph topology
- **Computer Vision Bootcamp** — OpenCV University (Grade: 94%) — \[suspicious link removed\]
- **TensorFlow Keras Bootcamp** — OpenCV University (Grade: 92%) — \[suspicious link removed\]
- **Generative AI: AI Agents & RAG** — IBM via Coursera — [Verify Certificate](https://www.google.com/search?q=https://coursera.org/share/34b513923f19fde20c8ea5f275306581)

## Local Usage & Deployment

`index.html` is completely self-contained (including the embedded official PDF resume) and requires no build step.

### Run Locally
Open `index.html` directly in any modern browser, or serve it locally:
```bash
python3 -m http.server 8000
```

### Deploy to GitHub Pages (`https://deepan2003.github.io`)
```bash
git init
git add index.html README.md
git commit -m "Deploy AI Engineer portfolio"
git branch -M main
git remote add origin https://github.com/deepan2003/deepan2003.github.io.git
git push -u origin main
```
Then enable **Settings → Pages → Branch: `main`** in your GitHub repository.
