---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I build"
        strings:
          - "production GenAI platforms"
          - "realtime voice AI agents"
          - "enterprise RAG systems"
          - "reliable ML infrastructure"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View My Work
          url: "#projects"
          icon: arrow-down
        - text: Get In Touch
          url: "#contact"
          icon: envelope

  - block: portfolio
    id: projects
    content:
      title: "Featured Projects"
      subtitle: "Production systems I led and shipped"
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: '*'
        - name: GenAI
          tag: GenAI
        - name: RAG
          tag: RAG
        - name: Voice AI
          tag: Voice AI
      default_button_index: 0
    design:
      columns: 3

  - block: tech-stack
    id: skills
    content:
      title: "Tech Stack"
      subtitle: "What I use to ship production AI"
      categories:
        - name: Languages
          items:
            - name: Python
              icon: devicon/python
            - name: C++
              icon: devicon/cplusplus
        - name: AI / ML
          items:
            - name: PyTorch
              icon: devicon/pytorch
            - name: TensorFlow
              icon: devicon/tensorflow
            - name: Hugging Face
              icon: custom/huggingface
            - name: OpenCV
              icon: devicon/opencv
            - name: Google ADK
              icon: hero/cpu-chip
        - name: Backend
          items:
            - name: FastAPI
              icon: devicon/fastapi
            - name: Node.js
              icon: devicon/nodejs
            - name: Redis
              icon: devicon/redis
            - name: MongoDB
              icon: devicon/mongodb
        - name: Cloud / Ops
          items:
            - name: Docker
              icon: devicon/docker
            - name: GCP
              icon: devicon/googlecloud
            - name: PostgreSQL
              icon: devicon/postgresql
            - name: GitHub Actions
              icon: brands/github
    design:
      style: grid
      show_levels: false

  - block: resume-experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      subtitle: "7+ projects shipped across 3 companies"
      items:
        - title: Lead Engineer
          company: HCL Technologies Limited
          company_url: 'https://www.hcltech.com/'
          company_logo: ''
          location: Noida, India
          date_start: '2025-06-01'
          date_end: ''
          description: |2-
            Tech lead for production GenAI platforms across finance automation, realtime voice AI, and regulatory search. Focus: architecture, latency, reliability, secure deployment, and operational handoff.

            **HCL Projects**

            - [IFRS](projects/ifrs-agents) — Gemini/Google ADK invoice anomaly detection and FP&A variance analysis with SAP data validation.
            - [AACA](projects/aaca-ai-contact-center) — Realtime voice AI with Twilio, OpenAI Realtime API, Milvus RAG, tool calling, and human handoff.
            - [SEBiSearch](projects/sebi-search-rag) — Offline regulatory RAG with Jina/BM25 retrieval, ModernBERT reranking, and grounded citations.
        - title: Senior Software Engineer
          company: PathPartner Technology (KPIT)
          company_url: ''
          company_logo: ''
          location: Bangalore, India
          date_start: '2021-07-01'
          date_end: '2025-05-31'
          description: |2-
            Shipped edge vision and accelerator software across computer vision, BEV segmentation, and deep learning kernel optimization.
        - title: Software Engineer Intern
          company: AgVerse Technology
          company_url: ''
          company_logo: ''
          location: Bangalore, India
          date_start: '2020-02-01'
          date_end: '2020-06-30'
          description: |2-
            Firebase telemetry, on-demand preprocessing modules, and Baum-Welch HMM parameter and state estimation.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      text: 'Discover Artificial Intelligence 2026 + IEEE ICRAIS 2023 — one Best Paper'
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: All Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Let's build something reliable together"
      text: |-
        Open to Staff/Lead roles in Applied AI and collaborations on voice agents and domain RAG.
        Fastest response by email.
      email: kumar.shiv.pms@gmail.com
      autolink: true
    design:
      columns: '1'

  - block: cta-card
    content:
      title: "Open to Opportunities"
      text: |-
        Lead Engineer with 5 years shipping GenAI, RAG, and Agentic AI to production.

        Let's discuss how I can help your team.
      button:
        text: 'Download Resume'
        url: uploads/resume.pdf
        new_tab: true
---
