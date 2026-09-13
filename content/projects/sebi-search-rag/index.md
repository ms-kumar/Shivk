---
title: "SEBI Search — Regulatory RAG Platform"
date: 2025-06-01
summary: "Production hybrid RAG and citation-grounded answers over SEBI legal and regulatory documents"
tags:
  - GenAI
  - RAG
tech_stack:
  - Python
  - FastAPI
  - Docling
  - Milvus
  - Jina v5
  - BM25
  - ModernBERT
  - vLLM
  - OpenAI
  - Redis
  - FAISS
  - Docker
featured: true
status: "Internal"
role: "Tech Lead"
duration: "4 months"
team_size: 3
highlights:
  - "80% retrieval hit rate, 75.8% nDCG"
  - "Citation-constrained grounded answers"
  - "100% offline air-gapped Docker deploy"
  - "Redis/FAISS caching + Prometheus health probes"
---

## Project Details

{{< project-details >}}
  {{< project-detail number="01" title="Document Pipeline" >}}Built a full RAG platform over thousands of SEBI legal and regulatory documents.{{< /project-detail >}}
  {{< project-detail number="02" title="PDF Understanding" >}}Parsed PDF files with Docling and created heading-aware document chunks.{{< /project-detail >}}
  {{< project-detail number="03" title="Semantic Retrieval" >}}Generated Jina v5 embeddings and stored them in Milvus for vector search.{{< /project-detail >}}
  {{< project-detail number="04" title="Hybrid Search" >}}Combined Jina semantic retrieval with BM25 keyword search for stronger recall.{{< /project-detail >}}
  {{< project-detail number="05" title="Reranking Quality" >}}Added ModernBERT cross-encoder reranking, reaching an 80% retrieval hit rate and 75.8% nDCG.{{< /project-detail >}}
  {{< project-detail number="06" title="Grounded Generation" >}}Implemented citation-constrained generation with vLLM/OpenAI, grounding answers to exact file, page, and order metadata.{{< /project-detail >}}
  {{< project-detail number="07" title="Production Reliability" >}}Added Redis and FAISS caching, Prometheus metrics, health probes, concurrency controls, and request timeouts.{{< /project-detail >}}
  {{< project-detail number="08" title="Offline Deployment" >}}Delivered 100% offline Docker Compose deployment for restricted SEBI environments on RHEL 9 air-gapped VMs.{{< /project-detail >}}
{{< /project-details >}}

## Tech Stack

{{< tech-stack >}}
  {{< tech-group title="Retrieval & NLP" items="Docling|Jina v5|Embeddings|BM25|ModernBERT|Reranker|vLLM|OpenAI APIs|Hybrid Search" >}}
  {{< tech-group title="Platform & Operations" items="Python|FastAPI|Milvus|Redis|FAISS|Prometheus|Docker|RHEL 9" >}}
{{< /tech-stack >}}

<!--more-->
