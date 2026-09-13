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

## Project Details

{{< project-details >}}
  {{< project-detail number="01" title="Realtime Voice Platform" >}}Built a microservices-based AI contact-center platform for realtime voice interactions.{{< /project-detail >}}
  {{< project-detail number="02" title="Low-Latency Voice Edge" >}}Developed the voice edge with FastAPI and WebSockets for streaming call audio.{{< /project-detail >}}
  {{< project-detail number="03" title="Control Plane" >}}Built a stateful control plane with FastAPI, MongoDB, and JWT authentication.{{< /project-detail >}}
  {{< project-detail number="04" title="Telephony Integration" >}}Bridged Twilio Media Streams to the OpenAI Realtime API using G.711 u-law audio.{{< /project-detail >}}
  {{< project-detail number="05" title="Speech Performance" >}}Delivered sub-second speech-to-speech interaction for live customer calls.{{< /project-detail >}}
  {{< project-detail number="06" title="RAG & Tool Calling" >}}Added Milvus RAG with tools for knowledge search, customer verification, and ticket actions.{{< /project-detail >}}
  {{< project-detail number="07" title="Agent Handoff" >}}Used Redis pub/sub for cross-instance events and live-agent handoff.{{< /project-detail >}}
  {{< project-detail number="08" title="Deployment Stack" >}}Packaged MongoDB, Redis, Milvus, MinIO, and Postgres with Docker Compose for Cloud Run readiness.{{< /project-detail >}}
{{< /project-details >}}

## Tech Stack

{{< tech-stack >}}
  {{< tech-group title="Voice & AI" items="Python|OpenAI Realtime API|Twilio|WebSockets" >}}
  {{< tech-group title="Backend & Data" items="FastAPI|Milvus|Redis|MongoDB|JWT" >}}
  {{< tech-group title="Deployment" items="Docker|MinIO|Postgres|Cloud Run" >}}
{{< /tech-stack >}}

<!--more-->
