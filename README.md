<h1 align="center">Muhammad Roshaan</h1>
<p align="center">
  Backend & Data Engineer · AI-Safety & LLM-Evaluation Researcher · Final-Year CS Student, SSUET Karachi
</p>

<p align="center">
  <a href="https://www.m-roshaan.me/"><img src="https://img.shields.io/badge/Portfolio-1F4E79?style=flat-square" alt="Portfolio"/></a>
  <a href="https://github.com/MRoshaan"><img src="https://img.shields.io/badge/GitHub-MRoshaan-181717?style=flat-square&logo=github" alt="GitHub"/></a>
</p>

I build backend systems and data pipelines that hold up under real load concurrency-safe transaction engines, ETL pipelines processing hundreds of thousands of records, and offline-first sync architectures. My focus areas: **distributed systems, data integrity, and API design**, built primarily in **Python**, with **Go** for deterministic tooling and **Java** for Spring Boot services.

**Currently exploring:** AI safety and evaluation: stress-testing LLMs, building evaluation harnesses to measure reliability and jailbreak resistance, and assessing biosecurity risks in AI systems. This research has produced co-authored workshop papers at NeurIPS 2026 (under review and forthcoming).

---

## Featured Engineering Projects

### [Sentinel - Real-Time Fraud Detection](https://github.com/MRoshaan/sentinel)
Fraud detection service combining real-time event processing with explainable AI and monitoring.
- Max-vote ensemble (Random Forest, XGBoost, LightGBM) achieving ~0.9995 ROC AUC on a 1.27M-sample test set
- FastAPI prediction endpoints with rate limiting and anomaly tracing for explainability (XAI)

**Stack:** Python · FastAPI · scikit-learn · XGBoost · LightGBM · Redis · PostgreSQL

### [Enterprise ETL & Inventory Pipeline](https://github.com/MRoshaan/enterprise-inventory-etl)
Automated pipeline that ingests, transforms, validates, and loads inventory data while raising operational alerts.
- Cleaned and bulk-loaded 540K+ records into a Supabase-backed PostgreSQL database
- Celery + Redis for scheduled background processing and real-time threshold alerts

**Stack:** Python · Celery · Redis · PostgreSQL · Supabase

### [SeatVault - Transaction-Safe Concurrency Engine](https://github.com/MRoshaan/SeatVault)
High-contention reservation backend built to prevent overselling under concurrent load.
- Redis distributed locking and PostgreSQL row locks for atomic inventory control
- Celery background workers for idempotent, payment-style workflows

**Stack:** Python · FastAPI · Redis · PostgreSQL · Celery

### [BooknScore - Offline-First Scoring & AI Service](https://github.com/MRoshaan/BooknScore)
Offline-first cricket scoring platform with zero-data-loss synchronization and a companion AI service.
- Dual-database design: local SQLite for offline use, Supabase for sync on reconnect
- Companion Python + Gemini AI service that converts raw match data into finished content

**Stack:** Flutter · SQLite · Supabase/PostgreSQL · Python · Gemini API

### [Geospatial Fleet Dispatch API](https://github.com/MRoshaan/edge-logistics-pipeline)
Serverless real-time fleet dispatch platform mapping nearby vehicles via geospatial queries.
- MongoDB 2dsphere indexing with `$geoNear` for proximity mapping
- FastAPI backend paired with a Next.js command-center UI over WebSockets

**Stack:** Python · FastAPI · MongoDB · Cloudflare Workers · WebSockets · Next.js

### [Dealer & Vehicle Inventory Module](https://github.com/MRoshaan/dealer-inventory-modular-monolith)
Multi-tenant modular monolith with tenant-aware data isolation and role-based access control.
- Java / Spring Boot with Spring Data JPA
- `X-Tenant-Id` isolation and custom query filtering per tenant

**Stack:** Java · Spring Boot · Spring Data JPA · Maven

---

## Featured Research

### [Agent Watchtower - Order-Invariant Causal Trace Verification](https://github.com/aaliyan1230/agent-watchtower)
*Collaborative research (open repo) · Verify-Agents & AI-WiLD Workshops @ NeurIPS 2026 (under review)*
- Built the Go canonical causal-DAG renderer with byte-stable checksums and a 160-cell serialization sweep over 40 seeded traces × 4 fault conditions
- Showed deterministic verdicts are order-invariant (0.000 flip rate) while live LLM judges flip on 55-75% of identical traces (cross-family κ 0.08-0.29 across Gemini, DeepSeek, and Kimi)
- Ran 240 live judge calls across three model families, kept 127+ tests green, and shipped a checksummed metrics artifact; PR #1 merged into main; authored the workshop paper

**Stack:** Go · Python · OpenTelemetry · LLM Evaluation · pytest

### [BitFracture - Quantization Error Taxonomy for Small Tool-Calling Models](https://github.com/MRoshaan/bitfracture)
*Primary author · SLM-Agents Workshop @ NeurIPS 2026 (forthcoming)*
- Pre-registered FP16-vs-NF4 study showing quantization breaks tool-calling discipline, not knowledge: missed required tool calls nearly tripled for Qwen3-1.7B (6.0% → 17.3%) while Qwen3-4B showed a powered null
- Designed a 7-class error taxonomy with bootstrap 95% CIs and a phase-gated run (pilot n=50, then powered n=150/cell) on BFCL tool-calling tasks

**Stack:** Python · bitsandbytes · BFCL · Qwen3 · Bootstrap Statistics

**Reviewer** — Verify-Agents Workshop @ NeurIPS 2026 (accepted Aug 2026)

---

## Skills

| Category | Technologies |
|---|---|
| **Languages** | Python, Go, Java, SQL |
| **Backend & APIs** | FastAPI, SQLAlchemy, REST APIs, WebSockets, Celery, Pydantic |
| **Databases** | PostgreSQL, MySQL, SQLite, MongoDB, Redis, Supabase |
| **Data & ML** | Pandas, NumPy, scikit-learn, XGBoost, LightGBM, Power BI, Hopsworks |
| **Research & Evaluation** | LLM Evaluation, Tool Calling, Fault Injection, Bootstrap Statistics, Guardrails, OpenTelemetry, pytest |
| **Tools** | Git, Docker, Jupyter |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MRoshaan&show_icons=true&count_private=true&hide=prs&theme=blue-green" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MRoshaan&theme=blue-green&hide_border=true" alt="GitHub Streak" height="165"/>
</p>

<p align="center"><i>Open to backend engineering, data engineering, AI/ML, and AI-safety / LLM-evaluation research opportunities.</i></p>
