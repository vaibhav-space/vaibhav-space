<h1 align="center">Vaibhav Dubey</h1>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D2FF&center=true&vCenter=true&width=900&lines=Backend+%26+Applied+AI+Systems+Engineer;Node.js+%2F+TypeScript+%7C+Python+%2F+FastAPI;Model+Context+Protocol+(MCP)+Infrastructure;LangGraph+Deterministic+Agentic+Systems;Fine-Tuned+Multimodal+Vision+(SigLIP+2);High-Throughput+Distributed+Queues+(BullMQ)" alt="Typing Animation" />
</div>

<p align="center">
  I build backend infrastructure for AI agents and multimodal retrieval systems that run against real catalogs, real orders, and real users. My main stack is <b>Node.js / TypeScript</b> and <b>Python / FastAPI</b>. I am currently Backend Lead on Jewelmount at CodBizz Technologies, Gujarat, India.
</p>

<p align="center">
  <b>Open to backend and applied AI roles.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vaibhav-space/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
  <a href="mailto:vaibhavdubey0902@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
  <a href="https://github.com/vaibhav-space/vindex"><img src="https://img.shields.io/badge/vindex_Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="vindex Repo" /></a>&nbsp;
  <a href="https://vaibhav-space.github.io/vindex/"><img src="https://img.shields.io/badge/vindex_Docs-0284C7?style=for-the-badge&logo=readthedocs&logoColor=white" alt="vindex Docs" /></a>
</p>

---

## Open source

### [vindex](https://github.com/vaibhav-space/vindex): local video knowledge compiler

A local-first compiler that turns video into structured, searchable artifacts (audio transcripts, OCR of keyframes, scene-level summaries) for offline RAG pipelines.

* PyAV and PySceneDetect handle decoding and scene detection for fully offline processing.
* Combines faster-whisper, PaddleOCR-VL, and Qwen2-VL (via Apple MLX) with Sentence-Transformers embeddings.
* Modular FastAPI backend with strict Pydantic v2 schemas, so outputs are typed and reproducible.

[Repository](https://github.com/vaibhav-space/vindex) · [Documentation](https://vaibhav-space.github.io/vindex/)

---

## Production work

*Company codebases are private, so the live products are linked instead.*

### Jewelmount: B2B jewelry platform

Backend Lead, CodBizz Technologies · [Website](https://www.jewelmounts.com/) · [iOS](https://apps.apple.com/in/app/jewelmount/id6450712246) · [Android](https://play.google.com/store/apps/details?id=com.jewelmounts.app)

#### AI agent infrastructure
* Built a Model Context Protocol (MCP) layer connecting the B2C storefront to external AI coding agents (Claude Code, Codex). It exposes 48 Zod-validated tools over JSON-RPC across 250K+ luxury SKUs, with deterministic read-only and zero-hard-delete safety guardrails.
* Built one-prompt merchandising workflows and closed-loop growth automation across Google Search Console, Merchant Center, and Google/Meta Ads, driven by real-time margin and stock signals.
* Built a production B2B agentic assistant on LangGraph with 17 custom tools and deterministic state machines for catalog generation, invoicing, order lifecycles, and merchant communication. Includes a versioned LLM-to-UI protocol for streaming generative UI and cross-session semantic memory.

#### Search and retrieval
* Fine-tuned SigLIP 2 to match noisy mobile-camera photos with clean CAD renders. Deployed on FastAPI + Qdrant across 400K+ designs, improving Top-1 accuracy by 35%.
* Built a domain-specific semantic search engine on transformer embeddings, reducing zero-result searches by 80%.
* Optimized a 206K-record catalog media pipeline with CDN-optimized WebP streaming, cutting LLM token overhead by 95%+ with sub-100ms asset delivery.

#### Data pipelines
* Built a catalog and inventory synchronization pipeline with Node.js, BullMQ, and Redis that published 250,000+ eBay listings through the eBay Seller API, with rate limiting, retry queues, and fault tolerance.

---

### Brainpad: gamified learning platform

Backend Migration Lead, CodBizz Technologies · [Play Store](https://play.google.com/store/apps/details?id=com.brainpad.live1010&hl=en_IN)

* Led migration of a legacy PHP backend to a unified Node.js / TypeScript and PostgreSQL architecture across 5 mobile apps serving 50,000+ active users. API latency dropped from 2.5s to 200ms at 99.5% uptime.
* Consolidated services into a shared data layer with Redis caching for progression tracking. Play Store ratings rose from 3.2 to 4.5.
* Built an event-driven lifecycle pipeline on the WhatsApp Business API for onboarding and progression messaging, lifting paid subscription conversions by 35%.

---

## Stack

### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend & Systems
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Model Context Protocol](https://img.shields.io/badge/Model_Context_Protocol_(MCP)-4F46E5?style=for-the-badge&logo=anthropic&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-E11D48?style=for-the-badge&logo=redis&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logo=api&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=websocket&logoColor=white)
![JSON-RPC](https://img.shields.io/badge/JSON--RPC-8A2BE2?style=for-the-badge&logo=json&logoColor=white)

### AI & Retrieval
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![SigLIP 2](https://img.shields.io/badge/SigLIP_2-FF6B6B?style=for-the-badge&logo=huggingface&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC2626?style=for-the-badge&logo=qdrant&logoColor=white)
![Sentence-Transformers](https://img.shields.io/badge/Sentence--Transformers-FF9800?style=for-the-badge&logo=huggingface&logoColor=white)
![Semantic Search](https://img.shields.io/badge/Semantic_Search-9C27B0?style=for-the-badge&logo=search&logoColor=white)

### Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Cloud, DevOps & Media
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-4CAF50?style=for-the-badge&logo=github-actions&logoColor=white)
![FFmpeg & PyAV](https://img.shields.io/badge/FFmpeg_/_PyAV-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
