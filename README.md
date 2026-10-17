# Prateek Kharwar

**Data Engineer & Analytics Engineer** · IIT Roorkee  
[LinkedIn](https://www.linkedin.com/in/prateek-kharwar-a7764b270/) · [X (Twitter)](https://x.com/kharwarp02) · [GitHub Repositories](https://github.com/Khprateek?tab=repositories)

> Building reliable, scalable data pipelines, Kimball-modeled warehouses, and production-grade data platforms. Focused on dbt, Airflow, DuckDB, BigQuery, and applied GenAI.

---

## 🛠 Featured Engineering Projects

### 1. [Supply Chain & Inventory Optimization Hub](https://github.com/Khprateek/Supply-Chain-Inventory-Optimization-Hub)
*Enterprise supply chain analytics platform over a 9.5M+ row warehouse.*
- **Scale & Architecture**: Processed **9.5M+ rows** across 18 Parquet files using **DuckDB**, structured via **36 dbt models** with an SCD Type 2 snapshot for historical tracking.
- **Data Quality & Testing**: Implemented **131 automated data tests** enforcing referential integrity, uniqueness, and custom business rules.
- **Analytics & BI**: Designed interactive Power BI dashboards with dynamic ABC/XYZ segmentation, lead-time variance simulation, and DAX/VertiPaq memory optimization.
- **Tech Stack**: `Python` · `DuckDB` · `Parquet` · `dbt` · `Power BI` · `DAX`

---

### 2. [IndiaWeatherFlow](https://github.com/Khprateek/End-to-End-Weather-Data-Pipeline-GCP-AWS-dbt-Airflow-)
*Automated end-to-end cloud weather data pipeline.*
- **Ingestion & Orchestration**: Automated hourly batch ingestion for 10 Indian cities via OpenWeatherMap API using **Apache Airflow in Docker**, loading validated data directly into **Google BigQuery**.
- **Transformation Layer**: Structured a 3-layer **dbt pipeline** (staging, intermediate, and marts) for clean dimensional analytics.
- **CI/CD & Code Quality**: Enforced linting and testing via **GitHub Actions**, `pytest`, and `Ruff`, serving live metrics to a Looker Studio dashboard.
- **Tech Stack**: `Python` · `Apache Airflow` · `Docker` · `Google BigQuery` · `dbt` · `Looker Studio` · `GitHub Actions`

---

### 3. [GenAI Analytics Copilot](https://github.com/Khprateek/GenAI_Ecommerce_Analytics_Copilot)
*Modern e-commerce data warehouse paired with a natural-language analytics copilot.*
- **Data Warehouse**: Engineered a Kimball star-schema warehouse on **Google BigQuery** backed by **19 dbt models** and 40+ automated data tests.
- **GenAI Copilot**: Integrated **Gemini API** and **Streamlit** to generate natural-language-to-SQL conversions, automated anomaly detection, and business summaries.
- **Tech Stack**: `Python` · `Apache Airflow` · `Google BigQuery` · `dbt` · `Gemini API` · `Streamlit`

---

## 🌐 Open Source Contributions

[![Contributor](https://img.shields.io/badge/1st%20PR%20MERGED-KESTRA-1F232C?style=for-the-badge&logo=github&logoColor=200062&labelColor=CDC5FF)](https://kestra.io/community?from=github-badge)

- **[Kestra](https://github.com/kestra-io/kestra)**: Contributed to open-source workflow orchestration.
- **[Google / dpsynth](https://github.com/google/dpsynth)**: Contributed cross-platform development setup & documentation for WSL2/Windows.

---

## 💻 Technical Arsenal

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages & Querying** | Python, SQL (BigQuery, T-SQL, DuckDB), C++ |
| **Data Engineering & Modeling** | dbt, Apache Airflow, DuckDB, Apache Spark, pandas, NumPy |
| **Cloud & Storage** | Google Cloud Platform (BigQuery, Cloud Storage), Microsoft SQL Server |
| **DataOps & CI/CD** | Docker, Git, GitHub Actions, pytest, Ruff |
| **BI & Applied AI** | Power BI, Looker Studio, Streamlit, Gemini API |

---
