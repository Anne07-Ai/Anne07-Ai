# Lakshmi Anne

Principal AI Engineer based in Milton Keynes, UK. Currently at **Axiom GRC (WorkNest)** leading the AI layer of an automated penetration-testing platform — a deterministic-spine, bounded-agent vulnerability reporting engine on AWS Bedrock + Claude, where LLMs write prose but are structurally forbidden from inventing or altering a security fact.

9+ years building production AI/ML across cybersecurity, finance, retail, hospitality, and energy — real-time fraud detection, RAG and GenAI, demand forecasting, geospatial ML, and computer vision. Specialist in secure-by-design AI: guardrail-gated pipelines, prompt-injection defence on untrusted inputs, and OWASP-aligned architecture for LLM and agentic systems.

MSc Finance, University of Hertfordshire (2024). Microsoft Azure AI Engineer Associate, Google Cloud Professional ML Engineer, AWS ML Specialty certified.

---

## What I'm working on right now

**Axiom GRC (WorkNest) — Principal AI Engineer · 2026–present**
Leading the architecture and delivery of an **AI Gateway & agentic vulnerability reporting platform** for automated penetration testing. The engine turns raw scanner findings into client-ready vulnerability reports through a deterministic pipeline — `freeze → writer → QA → gate → reviser → render` — where rule-based components own every security fact (CVEs, CVSS scores, severity) and LLMs are bounded to structured prose generation, summarisation, and QA. A deterministic gate verifies every claim against a frozen evidence snapshot and the NVD, structurally preventing hallucinated or unverifiable findings from reaching a report. Built on Python, FastAPI, AWS Bedrock, Claude, LangGraph, and PostgreSQL, with a migration roadmap from a serial worker toward a graph-based architecture with parallel per-finding processing.

---

## Open source

**[`enterprise-ai-platform`](https://github.com/Anne07-Ai/enterprise-ai-platform)** — a production reference architecture for multi-tenant RAG with tool-using agents. FastAPI + Postgres RLS for tenant isolation, transactional outbox shipping events to Kafka, async ingestion + embedding workers, semantic search over pgvector, and an Anthropic Claude agent with `search_documents` / `get_document` tools and SSE-streamed responses. Apache 2.0.

[![CI](https://github.com/Anne07-Ai/enterprise-ai-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/Anne07-Ai/enterprise-ai-platform/actions/workflows/ci.yml)

---

## Selected production work

| Where | What I built | Outcome |
|---|---|---|
| **Axiom GRC (WorkNest)** — current | Agentic AI vulnerability reporting engine — deterministic `freeze → writer → QA → gate → reviser → render` pipeline on AWS Bedrock + Claude + LangGraph; NVD-grounded fact verification; prompt-injection defence on untrusted scan inputs | Structurally zero hallucinated CVEs reaching client reports; auditable, fact-grounded pipeline |
| HSBC · 2025–2026 | Real-time fraud detection platform — Kafka streaming + XGBoost / PyTorch ensembles, FastAPI risk scoring, Redis caching, FCA + PCI-DSS compliant | Screens 1M+ transactions/day at sub-100ms latency; reduced false positives vs. legacy rules |
| Marriott International · 2022–2024 | AI hospitality analytics platform — SpaCy NLP + GPT-4 insight generation over 200K+ guest reviews/yr, RAG-grounded responses, FastAPI + Power BI delivery to 30+ UK hotels | Daily managerial dashboards replaced quarterly PDFs; measurable CSAT improvement |
| Tesco · 2021–2022 | Demand forecasting + recommendations — Prophet + XGBoost on Spark pipelines, Airflow orchestration, FastAPI on Azure ML, 10K+ SKUs | ~£2M est. annual inventory savings; merch team adopted into weekly planning |
| StormGeo · 2018–2021 | Storm-impact forecasting — ARIMA / Prophet + PyTorch CNN fusing satellite, radar, and claims data across 50+ regions, 2TB/month ingestion, Tableau client dashboards | Insurance client reported ~£1.5M avoided claims in year one |
| Flipkart · 2016–2018 | Phone damage detection — TensorFlow/Keras CNN behind a Flask API, AWS S3 image pipelines | ~3× faster than manual inspection on the refurbishment line |

---

## Stack

**Languages & APIs.** Python, SQL, FastAPI, AsyncIO, REST, gRPC.

**AI & LLMs.** AWS Bedrock, Claude, GPT-4, LangGraph, LangChain, RAG, structured outputs, tool calling, multi-agent systems, guardrails & evaluation, FAISS, SpaCy, Transformers (BERT).

**AI security.** OWASP LLM Top 10, prompt-injection defence, guardrail-gated pipelines, fact-grounding / CVE validation (NVD), data-residency controls.

**Classic ML.** XGBoost, PyTorch, TensorFlow, ARIMA / Prophet, YOLOv8, OpenCV.

**Data & streaming.** Apache Kafka, Spark, Airflow, dbt, Delta Lake, PostgreSQL + pgvector, MongoDB, Redis, Neo4j.

**Cloud & MLOps.** Azure (AKS, ML, Data Factory), AWS (S3, EC2, Bedrock, SageMaker), GCP Vertex AI, MLflow, Docker, Kubernetes, GitHub Actions, Azure DevOps.

**Observability & testing.** OpenTelemetry, Prometheus, Grafana, Loki, Tempo, Pytest, Evidently AI.

---

## Get in touch

- **Email:** hello@lakshmianne.uk
- **LinkedIn:** [lakshmi-anne](https://www.linkedin.com/in/lakshmi-anne-b16420342/)
- **Website:** [lakshmianne.uk](https://lakshmianne.uk)
- **Location:** Milton Keynes, UK
- **Open to:** Principal / Lead AI Engineer, AI Architect, ML Platform, AI Security roles
