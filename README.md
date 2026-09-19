<h1 align="center">Laila Khezaz</h1>
<p align="center"><b>Data Engineer</b> — lakehouses, dbt, and the contracts that keep them honest</p>

<p align="center">
<a href="mailto:laila.khezaz@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/leila-k-a57779336/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Casablanca%2C%20Morocco-lightgrey?style=for-the-badge&logo=googlemaps&logoColor=333" />
</p>

<p align="center"><i>"Data engineering is the intersection of security, data management, DataOps, data architecture, orchestration, and software engineering."</i><br/>— Joe Reis &amp; Matt Housley</p>

---

I build the pipelines that feed the dashboards — not the dashboards themselves. Contract-validated ingestion. Medallion architecture that fails loudly instead of lying quietly. Enough dbt tests that "it works on my machine" isn't a sentence I have to say.

**Right now**
- 🏭 Finishing **FPLIP** — my end-of-year manufacturing lakehouse internship
- 🧪 Building **Ledger** — a bitemporal feature store that catches look-ahead bias
- 🗂️ Designing a **Governed Vector Data Platform** — lineage + quality gates for embeddings

Every real architectural decision gets an ADR — including the ones where I picked the boring tool on purpose.

---

## 📊 Activity

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=laila-kz&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=laila-kz&layout=compact&hide_border=true" />
</p>

---

## 🚀 Projects

### 🏭 FPLIP — Factory Performance & Loss Intelligence Platform
Zero-budget manufacturing lakehouse built against a real production constraint (BigQuery Sandbox forbids DML) — solved with partition-decorator loads and a hand-rolled DDL-only SCD2. 18 ADRs document every major call.

`BigQuery` `dbt` `Airflow` `FastAPI` `Superset` `scikit-learn`
![status](https://img.shields.io/badge/status-internship%20project-blue?style=flat-square) [write-up on request](mailto:laila.khezaz@gmail.com)

### 🛒 E-Commerce Lakehouse Platform
Full Bronze→Silver→Gold lakehouse from raw CSVs: schema contracts with quarantine, incremental + watermarked + deduplicated Delta jobs, 13 dbt models, cross-layer reconciliation checks.

`PySpark` `Delta Lake` `dbt` `Airflow` `MinIO` `DuckDB`
![status](https://img.shields.io/badge/status-live-brightgreen?style=flat-square) [repo →](https://github.com/laila-kz/DataLakeHouse_project2-)

### 🛡️ Agentic Delta Guard
Data-quality gatekeeper for AI-agent tool events: schema/bounds/freshness contracts, Bronze-vs-quarantine routing, 7 FastMCP tools for enforcement and audit, Kafka + Spark Structured Streaming ingestion.

`Python` `dbt` `Delta Lake` `PySpark` `Kafka` `FastMCP`
![status](https://img.shields.io/badge/status-write--up%20on%20request-blue?style=flat-square) [contact me](mailto:laila.khezaz@gmail.com)

### 📈 End-to-End Analytics Engineering Pipeline
Snowflake VARIANT sources transformed through 7 dbt models (staging → dimensions → incremental facts), hash-based surrogate keys, 47 generic tests, dbt CI on GitHub Actions.

`Snowflake` `dbt` `SQL` `Jinja` `GitHub Actions`
![status](https://img.shields.io/badge/status-live-brightgreen?style=flat-square) [repo →](https://github.com/laila-kz/end-to-end-analytics-engineering-pipeline)

### 📒 Ledger
Bitemporal, point-in-time feature store with a canary engine that flags look-ahead bias before it reaches a model.

`Python` `DuckDB` `Polars`
![status](https://img.shields.io/badge/status-in%20progress-yellow?style=flat-square)

### 🗂️ Governed Vector Data Platform
Catalog, lineage, and a quality gate in front of embedding pipelines — so a bad vector can't silently ship.

`Python` `OpenLineage/Marquez` `FastAPI`
![status](https://img.shields.io/badge/status-in%20progress-yellow?style=flat-square)

---

## 🧭 How I Work

- Data contracts before pipelines — schema, bounds, and freshness checks are part of the design, not an afterthought
- ADRs for every architectural decision, including tool choices I deliberately didn't make
- dbt tests and CI as a baseline, not a bonus feature
- No AI/agent framing on a project unless the AI component is doing something a deterministic pipeline genuinely couldn't

---

## 🛠️ Stack

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

---

## 📜 Certifications

- SQL (Advanced) — HackerRank
- Associate Data Engineer — DataCamp
- Databricks Fundamentals & Deploy Workloads with Lakeflow Jobs — Databricks Academy
- dbt Fundamentals — dbt Labs
- Data Engineering on AWS: Foundations — AWS
- Data Governance, GDPR & Data Privacy Fundamentals — DataCamp
- OCI AI Foundations — Oracle
- Microsoft Fabric Data Engineer (DP-700) — in progress

---

<p align="center">Open to Data Engineer / AI Engineer internships (4–6 months), Europe or Canada.</p>
