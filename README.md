
<h1 align="center">Leila Khezaz</h1>
<p align="center"><b>Data Engineer</b> — lakehouses, dbt, and the contracts that keep them honest</p>
<p align="center">Safi / Casablanca, Morocco &nbsp;·&nbsp; <a href="mailto:leilakhezaz07@gmail.com">Email</a> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/leila-k-a57779336/">LinkedIn</a>

---
> "Data engineering is the intersection of security, data management, DataOps, data architecture, orchestration, and software engineering." — Joe Reis & Matt Housley

Hi, I’m Laila. I build reliable data infrastructure and lakehouses with a strong focus on data validation, test coverage, and clear architecture. Right now, I'm wrapping up my manufacturing lakehouse internship (FPLIP) and working on two main projects: Ledger, a bitemporal feature store to prevent data leakage, and a Governed Vector Data Platform for reliable embedding pipelines.

I document key decisions with ADRs—favoring simple, proven tools over unnecessary complexity.
## Projects

| Project | What it proves | Stack | Status |
|---|---|---|---|
| **FPLIP** — Factory Performance & Loss Intelligence Platform | Zero-budget manufacturing lakehouse built against a real production constraint (BigQuery Sandbox forbids DML) — solved with partition-decorator loads and a hand-rolled DDL-only SCD2. 18 ADRs document every major call. | BigQuery · dbt · Airflow · FastAPI · Superset · scikit-learn | Internship project — [write-up on request](mailto:leilakhezaz07@gmail.com) |
| **E-Commerce Lakehouse Platform** | Full Bronze→Silver→Gold lakehouse from raw CSVs: schema contracts with quarantine, incremental + watermarked + deduplicated Delta jobs, 13 dbt models, cross-layer reconciliation checks. | PySpark · Delta Lake · dbt · Airflow · MinIO · DuckDB | [Repo](https://github.com/laila-kz/DataLakeHouse_project2-) |
| **Agentic Delta Guard** | Data-quality gatekeeper for AI-agent tool events: schema/bounds/freshness contracts, Bronze-vs-quarantine routing, 7 FastMCP tools for enforcement and audit, Kafka + Spark Structured Streaming ingestion. | Python · dbt · Delta Lake · PySpark · Kafka · FastMCP | [Write-up on request](mailto:laila.khezaz@gmail.com) |
| **End-to-End Analytics Engineering Pipeline** | Snowflake VARIANT sources transformed through 7 dbt models (staging → dimensions → incremental facts), hash-based surrogate keys, 47 generic tests, dbt CI on GitHub Actions. | Snowflake · dbt · SQL · Jinja · GitHub Actions | [Repo](https://github.com/laila-kz/end-to-end-analytics-engineering-pipeline) |
| **Ledger** | Bitemporal, point-in-time feature store with a canary engine that flags look-ahead bias before it reaches a model. | Python · DuckDB · Polars | In progress |
| **Governed Vector Data Platform** | Catalog, lineage, and a quality gate in front of embedding pipelines — so a bad vector can't silently ship. | Python · OpenLineage/Marquez · FastAPI | In progress |

## How I work

- Data contracts before pipelines — schema, bounds, and freshness checks are part of the design, not an afterthought
- ADRs for every architectural decision, including tool choices I deliberately didn't make
- dbt tests and CI as a baseline, not a bonus feature
- No AI/agent framing on a project unless the AI component is doing something a deterministic pipeline genuinely couldn't

## Stack

**Core**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=flat&logoColor=white)

**Warehouses & Storage**
<br>
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlebigquery&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white)

**Quality, CI/CD & Infra**
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

**Streaming & Serving**
<br>
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**AI / Analytics-adjacent**
<br>
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

## Certifications

- SQL (Advanced) — HackerRank
- Associate Data Engineer — DataCamp
- Databricks Fundamentals & Deploy Workloads with Lakeflow Jobs — Databricks Academy
- dbt Fundamentals — dbt Labs
- Data Engineering on AWS: Foundations — AWS
- Data Governance, GDPR & Data Privacy Fundamentals — DataCamp
- OCI AI Foundations — Oracle
- Microsoft Fabric Data Engineer (DP-700) — in progress

## Get in touch

Open to Data Engineer / AI Engineer internships (4–6 months), Europe or Canada. Reach me at [laila.khezaz@gmail.com](mailto:leilakhezaz07@gmail.com) or on [LinkedIn]([https://linkedin.com/in/laila-khezaz](https://www.linkedin.com/in/leila-k-a57779336/)).
