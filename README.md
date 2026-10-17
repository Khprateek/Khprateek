# Prateek Kharwar

**Data Engineer & Analytics Engineer** · IIT Roorkee  
[LinkedIn](https://www.linkedin.com/in/prateek-kharwar-a7764b270/) · [X (Twitter)](https://x.com/kharwarp02) · [GitHub Repositories](https://github.com/Khprateek?tab=repositories)

> Data Engineer specializing in scalable pipeline orchestration, dimensional modeling, and analytical data engines. Active open-source contributor to orchestration and data tooling ecosystems.

---

## 🌐 Open Source Contributions

[![Kestra Contributor](https://img.shields.io/badge/PRs%20Merged-KESTRA-1F232C?style=flat-square&logo=github&logoColor=white&labelColor=5932EA)](https://github.com/kestra-io)

### **[Kestra](https://github.com/kestra-io)** — Open-Source Declarative Orchestrator

#### 🔹 [kestra-io/blueprints #1636](https://github.com/kestra-io/blueprints/pull/1636) · **Out-of-Order CDC Log Compaction & ASOF Merge with DuckDB**
- Designed an end-to-end data pipeline blueprint solving out-of-order Change Data Capture (CDC) events using DuckDB within Kestra.
- Implemented point-in-time state reconstruction using temporal `ASOF` joins and window functions to merge disordered streaming mutations into idempotent Parquet snapshots.

#### 🔹 [kestra-io/blueprints #2873](https://github.com/kestra-io/blueprints/pull/2873) · **Dynamic Event Sessionization & Inactivity Compaction with DuckDB**
- Engineered an analytical blueprint for sessionizing high-throughput event clickstreams based on dynamic inactivity thresholds.
- Orchestrated stateful session boundary generation and columnar compaction into partitioned analytical storage with zero external Spark/Flink dependencies.

#### 🔹 [kestra-io/kestra #19741](https://github.com/kestra-io/kestra/pull/19741) · **Core Engine: Loop Progress Visibility & Percentage Rounding**
- Resolved an execution monitoring issue in Kestra's core platform UI/execution layer, ensuring accurate loop progress tracking and integer percentage rounding for iterative tasks.

---

### **[Google / dpsynth](https://github.com/google/dpsynth)** — Differentially Private Synthetic Data
- Contributed cross-platform development setup and environment documentation for WSL2 / Windows developer workflows.

---

## 🛠 Featured Engineering Projects

- **[Supply Chain & Inventory Optimization Hub](https://github.com/Khprateek/Supply-Chain-Inventory-Optimization-Hub)**  
  *Enterprise supply chain analytics platform over a 9.5M+ row warehouse.*  
  Engineered 36 dbt models (including SCD Type 2 snapshots), 131 automated tests, and VertiPaq-optimized Power BI models for dynamic ABC/XYZ inventory segmentation and lead-time simulation.  
  `Python` · `DuckDB` · `Parquet` · `dbt` · `Power BI`

- **[IndiaWeatherFlow](https://github.com/Khprateek/End-to-End-Weather-Data-Pipeline-GCP-AWS-dbt-Airflow-)**  
  *Automated cloud weather data pipeline.*  
  Orchestrated hourly ingestion for 10 cities via Airflow (Docker) into BigQuery, modeled across 3 dbt layers (staging, intermediate, mart) with CI/CD linting (`pytest`, `Ruff`) and Looker Studio reporting.  
  `Python` · `Airflow` · `BigQuery` · `Docker` · `dbt` · `Looker Studio`

- **[GenAI Analytics Copilot](https://github.com/Khprateek/GenAI_Ecommerce_Analytics_Copilot)**  
  *Natural-language analytical engine for e-commerce data warehouses.*  
  Kimball star-schema warehouse on BigQuery (19 dbt models) paired with Gemini API and Streamlit for automated text-to-SQL querying and automated KPI anomaly insights.  
  `BigQuery` · `dbt` · `Airflow` · `Gemini API` · `Streamlit`

---

## 💻 Technical Arsenal

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages & Querying** | Python, SQL (BigQuery, T-SQL, DuckDB), C++ |
| **Orchestration & Data Engines** | Kestra, Apache Airflow, DuckDB, Apache Spark, pandas, NumPy |
| **Data Modeling & Storage** | dbt, Google BigQuery, Google Cloud Storage, Microsoft SQL Server, Parquet |
| **DataOps & Engineering Standards** | Docker, Git, GitHub Actions, pytest, Ruff, CI/CD |
| **BI & Applied AI** | Power BI (DAX / VertiPaq), Looker Studio, Streamlit, Gemini API |

---
