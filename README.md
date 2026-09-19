# Laila Khezaz

**Data Engineer (internship-track)** · AI & Data Science Engineering student, ENSA Safi — Bac+5, expected June 2027

Safi / Casablanca, Morocco · [laila.khezaz@gmail.com](mailto:laila.khezaz@gmail.com) · [LinkedIn](https://linkedin.com/in/laila-khezaz)

---

## About

I build data infrastructure, not dashboards-with-extra-steps: contract-validated ingestion, medallion pipelines that fail loudly when they should, and orchestration that survives a clean re-clone. Most of my recent work has been on lakehouse architecture (BigQuery, Snowflake, Delta Lake), dbt-based transformation and testing, and the governance layer that keeps both humans and AI agents from writing bad data to production.

Every non-trivial technical decision I make gets an ADR — including the ones where I chose *not* to use the trendier tool.

## Currently

- Finishing **FPLIP** (Factory Performance & Loss Intelligence Platform) — my end-of-year internship project, presenting to faculty this term
- Building **Ledger** — a bitemporal, point-in-time feature store with a look-ahead-bias canary engine (local-first Python/DuckDB/Polars, no Spark)
- Designing **Governed Vector Data Platform** — catalog, lineage (OpenLineage/Marquez), and a quality gate for embedding pipelines

## Selected Projects

| Project | What it proves | Stack | Link |
|---|---|---|---|
| **Factory Performance & Loss Intelligence Platform** | Zero-budget manufacturing lakehouse built against a real production constraint (BigQuery Sandbox forbids DML) — solved with partition-decorator loads and a hand-rolled DDL-only SCD2. 18 ADRs document every major call. | BigQuery, dbt, Airflow (GitHub Actions), FastAPI, Superset, scikit-learn | *repo private — factory data; write-up available on request* |
| **E-Commerce Lakehouse Platform** | Full Bronze→Silver→Gold lakehouse from raw CSVs: schema contracts with quarantine, incremental + watermarked + deduplicated Delta jobs, 13 dbt models, 3-task-group Airflow DAG, cross-layer reconciliation checks. | PySpark, Delta Lake, dbt, Airflow, MinIO, DuckDB | [GitHub](https://github.com/laila-kz/DataLakeHouse_project2-) |
| **Agentic Delta Guard** | Data-quality gatekeeper for AI-agent tool events: schema/bounds/freshness contract validation, Bronze-vs-quarantine routing, 7 FastMCP tools for enforcement and audit, streaming ingestion via Kafka + Spark Structured Streaming. | Python, dbt, Delta Lake, PySpark, Kafka, FastMCP, pytest | *repo private — case study available* |
| **End-to-End Analytics Engineering Pipeline** | Snowflake VARIANT semi-structured sources transformed through 7 dbt models (staging → dimensions → incremental facts), hash-based surrogate keys, 47 generic tests, dbt CI on GitHub Actions. | Snowflake, dbt, SQL, Jinja, GitHub Actions | [GitHub](https://github.com/laila-kz/end-to-end-analytics-engineering-pipeline) |

## How I work

- Data contracts before pipelines — schema, bounds, and freshness checks are part of the design, not an afterthought
- ADRs for every architectural decision, including tool choices I deliberately didn't make
- dbt tests and CI as a baseline, not a bonus feature
- No AI/agent framing on a project unless the AI component is doing something a deterministic pipeline genuinely couldn't

## Stack

| | |
|---|---|
| **Data Engineering** | Python, SQL, PySpark, dbt, Delta Lake, Airflow, Medallion Architecture |
| **Warehouses & Storage** | BigQuery, Snowflake, DuckDB, MinIO, PostgreSQL, Parquet |
| **Quality & CI/CD** | Data contracts, dbt tests, pytest, Docker, GitHub Actions, Terraform |
| **Streaming** | Apache Kafka, Spark Structured Streaming |
| **AI/Analytics-adjacent** | Feature engineering, ML pipelines, FastAPI, Streamlit, Plotly |

## Certifications

SQL (Advanced) — HackerRank · Associate Data Engineer — DataCamp · Databricks Fundamentals & Deploy Workloads with Lakeflow Jobs — Databricks Academy · dbt Fundamentals — dbt Labs · Data Engineering on AWS: Foundations — AWS · Data Governance, GDPR & Data Privacy Fundamentals — DataCamp · OCI AI Foundations — Oracle · Microsoft Fabric Data Engineer (DP-700, in progress)

## Get in touch

Open to Data Engineer / AI Engineer internships (4–6 months), Europe or Canada. Reach me at [laila.khezaz@gmail.com](mailto:laila.khezaz@gmail.com) or on [LinkedIn](https://linkedin.com/in/laila-khezaz).
