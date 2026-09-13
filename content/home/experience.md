---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Lead Engineer
    company: HCL Technologies Limited
    company_url: 'https://www.hcltech.com/'
    location: Noida, India
    date_start: '2025-06-01'
    date_end: ''
    description: |2-
        **IFRS — Invoice Anomaly Detection & FP&A Agents (Gemini / Google ADK, Vertex AI)**
        * Developed AI-powered Invoice Anomaly Detection Agent analyzing invoice risk using vendor history, confidence scoring, and evidence-backed signals for severity-based routing.
        * Developed Google ADK-powered FP&A Variance Analysis Agent automating SAP actuals vs budget/forecast/prior-period analysis with root-cause drivers and management-ready commentary.
        * Deployed on Vertex AI with PostgreSQL/Cloud SQL and Prometheus observability.
        * Tech: Python, GCP, GenAI, LLMs, Agents, Docker, FastAPI, Cloud SQL, Google ADK, Vertex AI, Agent Engine, Cloud Run.

        **AACA — Multi-service AI Contact-Center Platform**
        * Architected microservices platform separating latency-sensitive realtime voice edge (FastAPI + WebSocket) from stateful control plane (FastAPI + MongoDB + JWT).
        * Built bidirectional voice streaming bridging Twilio Media Streams with OpenAI Realtime API (g711 ulaw) for sub-second speech-to-speech latency.
        * Implemented RAG pipeline (OpenAI embeddings + Milvus) with GenAI tool calling (KB search, customer verify, ticket workflows).
        * Designed Redis pub/sub event bus for cross-instance WebSocket delivery and live agent handoff.
        * Tech: Python, GCP, GenAI, RAG, Twilio, Docker, FastAPI, OpenAI Realtime API, WebSockets, Redis, MongoDB, Milvus, JWT.

        **SEBI Search — RAG for Legal & Regulatory Documents**
        * Designed full RAG pipeline: PDF parsing (Docling) → heading-aware chunking → Jina v5 embeddings → Milvus → hybrid retrieval → reranking → citation-constrained generation.
        * Hybrid retrieval (Jina v5 + BM25) with ModernBERT cross-encoder reranking: 80% hit rate, 75.8% nDCG.
        * Mitigated hallucinations with citation-constrained generation (vLLM/OpenAI) grounded in file/page/order metadata.
        * 100% offline Docker Compose deployment for RHEL 9 / air-gapped VMs; Redis/FAISS caching, Prometheus metrics.
        * Tech: Python, FastAPI, Milvus, Jina v5, ModernBERT, vLLM, Redis, FAISS, Docker, Docling, BM25.

  - title: Senior Software Engineer
    company: PathPartner Technology (member of KPIT)
    company_url: ''
    location: Bangalore, India
    date_start: '2021-07-01'
    date_end: '2025-05-31'
    description: |2-
        **Image Stitching**
        * Converted feature-detection DL model to ONNX and target device formats for C++ pipeline integration.
        * Built C++ pipeline with DL feature detection + matching; deployed on Qualcomm device for real-time edge processing, reducing CPU runtime by 75%.
        * Tech: Python, C++, OOP, NumPy, PyTorch, Linux, QNN.

        **CES (BEV / Instance Segmentation)**
        * Trained SOLOv2 on custom datasets; OpenCV-based image blending for BEV outputs.
        * Built multi-model architecture: instance segmentation + multi-image classification; end-to-end train/test pipelines.
        * Used LIME for YOLO feature extraction and visualization.
        * Tech: Python, PyTorch, mmdet, OpenCV, Linux.

        **Deep Learning Kernels**
        * Built software suite with PyTorch/TensorFlow for high-performance training & inference on accelerators.
        * Debugged kernels, mapped PyTorch kernels to TPC kernels in C++; built operators with TPC kernels, converted models to ONNX (Netron).
        * Tech: Python, C++, PyTorch, TensorFlow, ONNX, Git, JIRA.

  - title: Software Engineer Intern
    company: AgVerse Technology Pvt. Ltd
    company_url: ''
    location: Bangalore, India
    date_start: '2020-02-01'
    date_end: '2020-06-30'
    description: |2-
        * Brought up Firebase server support to pull and analyze telemetry data.
        * Created on-demand data-preprocessing pipeline mechanism.
        * Performed Baum-Welch algorithm-based parameter and state estimation (HMM).
        * Tech: Python, Firebase, HMM, Pandas.

design:
  columns: '2'
---
