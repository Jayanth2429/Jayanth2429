# Hi, I'm Jayanth Damera 👋

### Data Engineer | Healthcare Data | Cloud & Streaming Systems

I’m a Data Engineer with nearly 5 years of experience building scalable data pipelines, streaming workflows, cloud-native data platforms, and analytics solutions.

My work focuses on transforming complex clinical, operational, and enterprise data into reliable, production-ready data products using Python, SQL, PySpark, Databricks, Spark, Kafka, and cloud platforms including Azure, AWS, and GCP.

I’m especially interested in designing systems that remain reliable when things go wrong: duplicate events, retries, schema changes, delayed data, failed API calls, and production-scale workloads.

---

## 🔧 Tech Stack

**Languages**  
Python · SQL · PySpark · Scala

**Data Engineering**  
Apache Spark · Databricks · Delta Lake · Apache Kafka · dbt · ETL/ELT

**Cloud**  
Microsoft Azure · AWS · Google Cloud Platform

**Data Platforms**  
Snowflake · BigQuery · PostgreSQL · SQL Server · DuckDB

**Healthcare & Integration**  
HL7 · FHIR · REST APIs · OAuth 2.0

**DevOps & Infrastructure**  
Terraform · Git · GitHub Actions · CI/CD · Docker

**Analytics**  
Power BI · Tableau · Dimensional Modeling

---

# 🚀 Featured Data Engineering Projects

## 🩺 [Healthcare Streaming Pipeline](https://github.com/Jayanth2429/healthcare-streaming-pipeline)

Production-style healthcare streaming pipeline built around public, deidentified MIMIC-IV clinical data.

**Architecture:**  
`MIMIC-IV → Kafka/Redpanda → PySpark Structured Streaming → Validation → Deduplication → Curated Data`

**Highlights**
- Replays historical clinical events as a real-time event stream
- PySpark Structured Streaming
- Schema validation and quarantine handling
- Event-time watermarking and deduplication
- Checkpointing and restart-safe processing
- Automated tests and GitHub Actions CI

**Tech:** `Python` `PySpark` `Kafka` `Structured Streaming` `Healthcare Data`

---

## 🏗️ [Reliable Lakehouse Pipeline](https://github.com/Jayanth2429/reliable-lakehouse-pipeline)

Production-style lakehouse pipeline using real CMS hospital data to demonstrate reliable incremental processing.

**Architecture:**  
`CMS Snapshot → Validation → Change Detection → Deduplication → MERGE → Audit`

**Highlights**
- Incremental ingestion
- Deterministic business keys
- SHA-256 content-based change detection
- Idempotent MERGE processing
- Audit metrics and data-quality controls
- Restart-safe pipeline design
- PySpark and Delta Lake implementation patterns

**Tech:** `Python` `PySpark` `Delta Lake` `Databricks` `Data Quality`

---

## 📊 [CMS Analytics Engineering](https://github.com/Jayanth2429/dbt-analytics-engineering)

Analytics engineering project built on real CMS hospital datasets using dbt and DuckDB.

**Architecture:**  
`CMS Public Data → Raw Layer → dbt Staging → Dimensions & Facts → Tests → BI Marts`

**Highlights**
- Real CMS hospital, readmissions, and quality datasets
- Staging, intermediate, and mart layers
- Conformed hospital and measure dimensions
- Fact models for readmissions and timely care
- Dimensional modeling
- Automated dbt data-quality and relationship tests
- Lineage and BI-ready analytical marts

**Tech:** `dbt` `SQL` `DuckDB` `Dimensional Modeling` `Healthcare Analytics`

---

## ☁️ [GCP Healthcare Data Platform](https://github.com/Jayanth2429/gcp-healthcare-data-platform)

Event-driven cloud data platform using real CMS hospital data and Google Cloud.

**Architecture:**  
`CMS Public Data → Cloud Run → Cloud Storage → Pub/Sub → BigQuery`

**Highlights**
- Cloud Run ingestion and loading services
- Immutable raw snapshots in Cloud Storage
- Pub/Sub event-driven processing
- BigQuery analytical and audit tables
- Cloud Scheduler automation
- Terraform infrastructure as code
- Least-privilege service accounts and IAM
- Python tests and Terraform validation in GitHub Actions

**Tech:** `GCP` `Cloud Run` `BigQuery` `Pub/Sub` `Cloud Storage` `Terraform` `Python`

---


## 🔄 [Resilient Batch Pipeline](https://github.com/Jayanth2429/resilient-batch-pipeline)

Production-style batch pipeline built on real Backblaze Drive Stats, designed to survive years of schema drift and operational failures.

**Architecture:**  
`Backblaze → Airflow → High-Water Mark → Schema Registry → Partitioned Parquet → Reliability Marts → Restatement`

**Highlights**
- Airflow orchestration and dependency management
- Incremental high-water-mark ingestion
- Schema drift and column-registry handling
- Resumable historical backfills
- Partition-aware reprocessing
- Reliability and survival analytics
- Historical restatement reporting
- Automated tests and GitHub Actions CI

**Tech:** `Python` `Airflow` `DuckDB` `Parquet` `Schema Evolution` `Data Quality`

---

## 🧠 Engineering Areas I Focus On

- Batch and streaming data pipelines
- Reliable and idempotent processing
- Healthcare interoperability and healthcare data
- Distributed processing with Spark
- Lakehouse architecture
- Cloud-native data platforms
- Data modeling and analytics engineering
- Data quality and observability
- Incremental ingestion and change detection
- Infrastructure as code
- Production troubleshooting and performance optimization

---

## 📚 Public Data Used in These Projects

My portfolio projects use real publicly accessible datasets where practical, including:

- **MIMIC-IV Demo** for deidentified clinical event streaming
- **CMS Provider Data Catalog** for hospital, readmissions, and quality analytics

Small deterministic fixtures are used only in unit tests so tests remain fast and reproducible.

No proprietary employer code, production patient data, internal schemas, or confidential business logic is included in these repositories.

---

## 🌱 What I'm Exploring

I’m continuing to expand this portfolio around:

- Databricks and Delta Lake patterns
- Event-driven architecture
- Healthcare interoperability
- Data observability
- Cloud infrastructure automation
- Analytics engineering
- AI-assisted data engineering workflows

---

## 🤝 Connect With Me

[LinkedIn](https://www.linkedin.com/in/jayanthd-data-engineer)

I'm always interested in connecting with people working in Data Engineering, healthcare technology, cloud platforms, distributed systems, and analytics engineering.
