<h1 align="center">Muhammad Roshaan</h1>
<p align="center">
  Backend & Data Engineer · Final-Year CS Student, SSUET Karachi
</p>

<p align="center">
  <a href="https://roshaanportfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1F4E79?style=flat-square" alt="Portfolio"/></a>
  <a href="https://github.com/MRoshaan"><img src="https://img.shields.io/badge/GitHub-MRoshaan-181717?style=flat-square&logo=github" alt="GitHub"/></a>
</p>

I build backend systems and data pipelines that hold up under real load concurrency-safe transaction engines, ETL pipelines processing hundreds of thousands of records, and offline-first sync architectures. My focus areas: **distributed systems, data integrity, and API design.**

---

## Featured Projects

### [Sentinel - Real-Time Fraud Detection](https://github.com/MRoshaan/sentinel)
Fraud detection service combining real-time event processing with explainable AI and monitoring.
- Max-vote ensemble (Random Forest, XGBoost, LightGBM) achieving ~0.9995 ROC AUC on a large test set
- FastAPI prediction endpoints with rate limiting and anomaly tracing for explainability (XAI)

**Stack:** FastAPI · scikit-learn · XGBoost · LightGBM

### [Enterprise ETL & Inventory Pipeline](https://github.com/MRoshaan/enterprise-inventory-etl)
Automated pipeline that ingests, transforms, validates, and loads inventory data while raising operational alerts.
- Cleaned and bulk-loaded 540K+ records into a Supabase-backed PostgreSQL database
- Celery + Redis for scheduled background processing and real-time threshold alerts

**Stack:** Python · Celery · Redis · PostgreSQL · Supabase

### [SeatVault - Transaction-Safe Concurrency Engine](https://github.com/MRoshaan/SeatVault)
High-contention reservation backend built to prevent overselling under concurrent load.
- Redis distributed locking and PostgreSQL row locks for atomic inventory control
- Celery background workers for idempotent, payment-style workflows

**Stack:** FastAPI · Redis · PostgreSQL · Celery

### [BooknScore - Offline-First Scoring & AI Service](https://github.com/MRoshaan/BooknScore)
Offline-first cricket scoring platform with zero-data-loss synchronization and a companion AI service.
- Dual-database design: local SQLite for offline use, Supabase for sync on reconnect
- Companion Python + Gemini AI service that converts raw match data into finished content

**Stack:** Flutter · SQLite · Supabase/PostgreSQL · Gemini API

### [Geospatial Fleet Dispatch API](https://github.com/MRoshaan/edge-logistics-pipeline)
Serverless real-time fleet dispatch platform mapping nearby vehicles via geospatial queries.
- MongoDB 2dsphere indexing for proximity mapping
- FastAPI backend paired with a Next.js command-center UI over WebSockets

**Stack:** FastAPI · MongoDB · WebSockets · Next.js

### [Dealer & Vehicle Inventory Module](https://github.com/MRoshaan/dealer-inventory-modular-monolith)
Multi-tenant modular monolith with tenant-aware data isolation and role-based access control.
- Java / Spring Boot with Spring Data JPA
- `X-Tenant-Id` isolation and custom query filtering per tenant

**Stack:** Java · Spring Boot · Spring Data JPA

---

## Skills

| Category | Technologies |
|---|---|
| **Languages** | Python, Java, SQL |
| **Backend & APIs** | FastAPI, SQLAlchemy, REST APIs, WebSockets, Celery, Pydantic |
| **Databases** | PostgreSQL, MySQL, SQLite, MongoDB, Redis, Supabase |
| **Data & ML** | Pandas, NumPy, scikit-learn, XGBoost, LightGBM, Power BI, Hopsworks |
| **Tools** | Git, Docker, Jupyter |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MRoshaan&show_icons=true&count_private=true&hide=prs&theme=blue-green" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MRoshaan&theme=blue-green&hide_border=true" alt="GitHub Streak" height="165"/>
</p>

<p align="center"><i>Open to backend, data engineering, and AI/ML internship opportunities.</i></p>
