---
title: "SEBI Search — Regulatory RAG Platform"
date: 2025-06-01
summary: "Hybrid search + rerank + grounded answers over SEBI docs"
tags:
  - GenAI
  - RAG
tech_stack:
  - Python
  - FastAPI
  - Milvus
  - Jina v5
  - ModernBERT
  - vLLM
  - Redis
  - Docker
links:
  - type: site
    url: https://www.hcltech.com/
    label: HCL (company project — code proprietary)
featured: true
status: "Live"
role: "Tech Lead"
duration: "4 months"
team_size: 3
highlights:
  - "80% retrieval hit rate, 75.8% nDCG"
  - "Citation-constrained grounded answers"
  - "100% offline air-gapped Docker deploy"
  - "Redis/FAISS caching + Prometheus"
---

Full RAG over thousands of SEBI docs: Docling PDF parsing → heading-aware chunking → Jina v5 embeddings → Milvus → hybrid (Jina + BM25) → ModernBERT reranking (80% hit rate, 75.8% nDCG) → citation-constrained vLLM/OpenAI generation with file/page/order grounding. Redis/FAISS caching, Prometheus metrics, 100% offline Docker Compose for RHEL 9 air-gapped VMs.

<!--more-->
