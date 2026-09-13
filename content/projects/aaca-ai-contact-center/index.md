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

- Built a microservices-based AI contact-center platform for realtime voice interactions.
- Developed a low-latency voice edge using FastAPI and WebSockets.
- Built a stateful control plane with FastAPI, MongoDB, and JWT authentication.
- Bridged Twilio Media Streams to the OpenAI Realtime API using G.711 u-law audio.
- Achieved sub-second speech-to-speech interaction for live calls.
- Added Milvus RAG with tool calling for knowledge search, customer verification, and ticket actions.
- Used Redis pub/sub for cross-instance events and live-agent handoff.
- Packaged MongoDB, Redis, Milvus, MinIO, and Postgres with Docker Compose.
- Prepared the services for Cloud Run deployment.

## Tech Stack

- Python, FastAPI, WebSockets, OpenAI Realtime API, Twilio, Milvus, Redis, MongoDB, Docker, MinIO, Postgres, JWT, and Cloud Run.

<!--more-->
