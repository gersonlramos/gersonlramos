# Gerson Ramos

**Data Engineer @ Compass UOL** — building cloud data platforms for enterprise clients (Stellantis, Pottencial Seguros).

I work on large-scale pipeline migrations and lakehouse architectures on AWS: Snowflake, Airflow, Spark, Kafka, Apache Iceberg. Background in Data Science and financial analysis, which shapes how I approach data problems — the pipeline exists to answer a business question, not the other way around.

📍 Mendes, RJ — Brazil · 🎓 B.Sc. Data Science · ☁️ AWS Certified: AI Practitioner + Cloud Practitioner

---

## What I'm working on

**GCP → AWS migration (Stellantis)** — Migrating ingestion and transformation pipelines from BigQuery + Cloud Functions to Snowflake + Apache Airflow (EKS Pod Operator), across 9 business domains and 3,000+ objects. Led the discovery and scoping, and built a resource-constrained scheduling simulation to estimate team allocation per domain.

**Medallion architecture (Pottencial Seguros)** — Bronze/Silver/Gold layers with Apache Iceberg on AWS Glue, batch processing via Spark on EMR across 1,000+ tables. Refactored Airflow orchestrations with custom sensors, eliminating 99% of worker blockage.

**Delivery tracking dashboard** — Python/Streamlit application with Monte Carlo delivery forecasting, Burn-up/CFD/Lead Time views, and an automated Jira extraction pipeline running on GitHub Actions.

---

## Featured projects

### [Store Sales — Time Series Forecasting](https://github.com/gersonlramos/Store-Sales---Time-Series-Forecasting)
`LightGBM` `Python` `Time Series` `Kaggle`

Forecasting 16 days of daily unit sales across 1,782 store × product-family series
(Corporación Favorita, Kaggle). Global LightGBM models scoring **RMSLE 0.38469** on a
held-out fortnight — 26% better than the strongest naive baseline — blending a direct
per-horizon forecaster with a recursive one, selected because their residuals decorrelate
(0.917) below seed-to-seed noise.

The point of the repository is the measurement record, not the score: every change tested,
every reversion, and two cases where a confidently reported effect turned out to be an
artefact once confounders were held fixed. Includes a naive control submitted for
calibration, a full changelog, and a feature dictionary documenting the legality of all 60
model inputs.

### [finance-notes-rag](https://github.com/gersonlramos/finance-notes-rag)
`RAG` `LlamaIndex` `BM25` `Ollama` `Python`

Fully local RAG pipeline (zero cloud cost) answering natural-language questions over
Flamengo's audited financial statements, 2022–2026 — OCR, embeddings, vector store and
LLM all running on a CPU-only laptop. 82% retrieval hit@k, 0.75 MRR, and 100% correct
abstention on unanswerable questions.

Every architecture choice was decided by measurement against a 20-question evaluation
set, including the ones that lost: table linearization cost 30 points and was reverted,
and lexical BM25 beat hybrid search by 24 points because the small multilingual embedder
is too coarse for accounting terminology.

### [redshift-dbt](https://github.com/gersonlramos/redshift-dbt)
`dbt` `AWS Redshift` `SQL`

ELT pipeline transforming the Northwind transactional dataset into analytical models, with temporal partitioning and layered transformations.

### [SQL_PySpark_Translator](https://github.com/gersonlramos/SQL_PySpark_Translator)
`PySpark` `Python` `Parsing`

Rule-based SQL-to-PySpark translator (no LLM) handling SELECT, JOIN, WHERE, ORDER BY, COALESCE and CASE WHEN, with correct table alias resolution — generating executable PySpark code.

### [Sales_Real_Time](https://github.com/gersonlramos/Sales_Real_Time)
`PostgreSQL` `Power BI` `Python`

Real-time sales monitoring system with automated PostgreSQL data simulation feeding dynamic Power BI dashboards for KPI tracking.

### [Postgres-Clean-Process-SuperStore](https://github.com/gersonlramos/Postgres-Clean-Process-SuperStore)
`PostgreSQL` `SQL` `Data Quality`

Data exploration and cleaning workflow on the SuperStore dataset, with SQL queries focused on data quality checks.

---

## Stack

| | |
|---|---|
| **Languages** | Python, SQL, R |
| **Data Engineering** | Snowflake, Apache Airflow, Spark / PySpark, Apache Iceberg, Kafka, dbt |
| **Cloud (AWS)** | Glue, EMR, EKS, S3, SageMaker, Lambda, ECS, Bedrock, Redshift |
| **Cloud (GCP)** | BigQuery, Cloud Functions, Dataflow |
| **ML & AI** | Scikit-Learn, XGBoost, TensorFlow, RAG, LangChain |
| **BI & Viz** | Streamlit, Plotly, Power BI, Tableau |
| **Ops** | Docker, Git, GitLab CI/CD, GitHub Actions |

---

## Certifications

**AWS** — Certified AI Practitioner · Certified Cloud Practitioner · Generative AI Technical Partner
**Oracle** — Cloud Infrastructure Certified Data Science Professional
**IBM** — Machine Learning Specialist (Associate) · Deep Learning with TensorFlow
**Google** — Advanced Data Analytics Certificate

---

## Contact

[LinkedIn](https://linkedin.com/in/gersonlramos) · [Email](mailto:gersonlopesr@gmail.com) · [Tableau Public](https://public.tableau.com/app/profile/gerson.lopes.ramos.junior/vizzes) · [DataCamp](https://www.datacamp.com/portfolio/gersonlopesr)

Open to opportunities in **Data Engineering** and **Machine Learning Engineering**.
