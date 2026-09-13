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

## Project Details

- Built a full RAG platform over thousands of SEBI regulatory documents.
- Parsed PDF files with Docling and created heading-aware document chunks.
- Generated document embeddings with Jina v5 and stored them in Milvus.
- Combined vector search with BM25 keyword retrieval for hybrid search.
- Added ModernBERT reranking, reaching an 80% retrieval hit rate and 75.8% nDCG.
- Implemented citation-constrained generation with vLLM and OpenAI-compatible APIs.
- Grounded answers to the source file, page number, and evidence order.
- Added Redis and FAISS caching for faster repeated searches.
- Added Prometheus metrics for system monitoring.
- Delivered a fully offline Docker Compose deployment for RHEL 9 air-gapped VMs.

<!--more-->
