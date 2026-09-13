---
title: "AACA — AI Contact-Center Platform"
date: 2025-08-01
summary: "Production realtime voice AI with OpenAI Realtime API, Milvus RAG, and live human handoff"
tags:
  - GenAI
  - RAG
  - Voice AI
tech_stack:
  - Python
  - GCP
  - GenAI / LLMs / Agents / RAG
  - FastAPI
  - WebSockets
  - OpenAI Realtime API
  - Twilio
  - Milvus
  - Redis
  - MongoDB
  - JWT
  - Docker
  - Cloud Run
featured: true
status: "Internal"
role: "Tech Lead"
duration: "3 months"
team_size: 4
highlights:
  - "Sub-second speech-to-speech latency"
  - "OpenAI embeddings + Milvus RAG tool calling"
  - "Redis pub/sub live human handoff"
  - "Cloud Run-ready horizontally scalable services"
---

## Project Details

{{< project-details >}}
  {{< project-detail number="01" title="Microservices Architecture" >}}Separated a latency-sensitive realtime voice edge from a stateful business control plane for independent scaling, deployment, and ownership.{{< /project-detail >}}
  {{< project-detail number="02" title="Low-Latency Voice Edge" >}}Developed FastAPI and WebSocket services for streaming call audio and realtime agent interactions.{{< /project-detail >}}
  {{< project-detail number="03" title="Telephony Integration" >}}Bridged Twilio Media Streams to the OpenAI Realtime API with native G.711 u-law audio to minimize transcoding overhead.{{< /project-detail >}}
  {{< project-detail number="04" title="Speech Performance" >}}Delivered bidirectional speech-to-speech interaction with sub-second voice AI latency.{{< /project-detail >}}
  {{< project-detail number="05" title="RAG & Tool Calling" >}}Used OpenAI embeddings and Milvus retrieval with tools for knowledge search, customer verification, and ticket workflows.{{< /project-detail >}}
  {{< project-detail number="06" title="Secure Operations" >}}Enforced identity verification before sensitive tool operations inside live voice sessions.{{< /project-detail >}}
  {{< project-detail number="07" title="Agent Handoff" >}}Designed Redis pub/sub channels for cross-instance WebSocket delivery, call assignment, transfer, and human handoff coordination.{{< /project-detail >}}
  {{< project-detail number="08" title="Deployment Stack" >}}Containerized MongoDB, Redis, Milvus, MinIO, and PostgreSQL with Docker Compose for Cloud Run horizontal scaling.{{< /project-detail >}}
{{< /project-details >}}

## Tech Stack

{{< tech-stack >}}
  {{< tech-group title="Voice & AI" items="Python|GCP|GenAI|LLMs|Agents|RAG|OpenAI Realtime API|Twilio|WebSockets" >}}
  {{< tech-group title="Backend & Data" items="FastAPI|Milvus|Redis|MongoDB|JWT" >}}
  {{< tech-group title="Deployment" items="Docker|Docker Compose|MinIO|Postgres|Cloud Run" >}}
{{< /tech-stack >}}

<!--more-->
