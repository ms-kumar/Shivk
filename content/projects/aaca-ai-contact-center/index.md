---
title: "AACA — AI Contact-Center Platform"
date: 2025-08-01
summary: "Realtime voice AI with Milvus RAG and live agent handoff"
tags:
  - GenAI
  - RAG
  - Voice AI
tech_stack:
  - Python
  - FastAPI
  - OpenAI Realtime API
  - Twilio
  - Milvus
  - Redis
  - MongoDB
  - Docker
links:
  - type: site
    url: https://www.hcltech.com/
    label: HCL (company project — code proprietary)
featured: true
status: "Live"
role: "Tech Lead"
duration: "3 months"
team_size: 4
highlights:
  - "Sub-second speech-to-speech latency"
  - "Milvus RAG with tool calling in live calls"
  - "Redis pub/sub cross-instance handoff"
  - "Cloud Run-ready microservices"
---

Microservices AI contact-center: latency-sensitive realtime voice edge (FastAPI + WebSocket) plus stateful control plane (FastAPI + MongoDB + JWT). Twilio Media Streams bridged to OpenAI Realtime API over WebSockets (g711 ulaw) for sub-second speech-to-speech. Milvus RAG with GenAI tool calling (KB search, customer verify, tickets). Redis pub/sub event bus for live agent handoff. Docker Compose (MongoDB, Redis, Milvus, MinIO, Postgres), Cloud Run-ready.

<!--more-->
