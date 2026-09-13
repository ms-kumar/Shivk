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

{{< project-details >}}
  {{< project-detail number="01" title="Document Pipeline" >}}Built a full RAG platform over thousands of SEBI regulatory documents.{{< /project-detail >}}
  {{< project-detail number="02" title="PDF Understanding" >}}Parsed PDF files with Docling and created heading-aware document chunks.{{< /project-detail >}}
  {{< project-detail number="03" title="Semantic Retrieval" >}}Generated Jina v5 embeddings and stored them in Milvus for vector search.{{< /project-detail >}}
  {{< project-detail number="04" title="Hybrid Search" >}}Combined vector retrieval with BM25 keyword search for stronger recall.{{< /project-detail >}}
  {{< project-detail number="05" title="Reranking Quality" >}}Added ModernBERT reranking, reaching an 80% retrieval hit rate and 75.8% nDCG.{{< /project-detail >}}
  {{< project-detail number="06" title="Grounded Generation" >}}Implemented citation-constrained generation with vLLM and OpenAI-compatible APIs.{{< /project-detail >}}
  {{< project-detail number="07" title="Evidence Traceability" >}}Grounded answers to the source file, page number, and evidence order.{{< /project-detail >}}
  {{< project-detail number="08" title="Performance & Deployment" >}}Added Redis and FAISS caching, Prometheus metrics, and offline Docker Compose deployment for RHEL 9 air-gapped VMs.{{< /project-detail >}}
{{< /project-details >}}

## Tech Stack

{{< tech-stack >}}
  {{< tech-group title="Retrieval & NLP" items="Docling|Jina v5|BM25|ModernBERT|vLLM|OpenAI APIs" >}}
  {{< tech-group title="Platform & Operations" items="Python|FastAPI|Milvus|Redis|FAISS|Prometheus|Docker|RHEL 9" >}}
{{< /tech-stack >}}

<!--more-->
