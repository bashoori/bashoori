<h1 align="center">Hi, I'm Bita 👋</h1>

<p align="center">
  <strong>Data Engineer</strong> · SQL Server & ETL · Microsoft Fabric & Azure · Data Quality<br/>
  <em>I build data pipelines that teams can trust in production.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bitaashoori/"><img src="https://img.shields.io/badge/LinkedIn-bitaashoori-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://bitadigitalhub.com"><img src="https://img.shields.io/badge/Website-bitadigitalhub.com-2E7D32?style=flat" alt="Website"></a>
  <a href="https://bashoori.github.io/hub"><img src="https://img.shields.io/badge/Portfolio-myHub-0e75b6?style=flat&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.youtube.com/@bitadigitalhub"><img src="https://img.shields.io/badge/YouTube-Data%20with%20Bita-FF0000?style=flat&logo=youtube&logoColor=white" alt="YouTube"></a>
  <a href="mailto:ashoori.bita@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 🎯 About me

I'm a Data Engineer in the Vancouver area with **5+ years** of hands-on work in ETL, SQL Server, Python and cloud data pipelines, across **healthcare, retail and enterprise** teams.

I care about how data systems behave after go-live. Most data problems I've fixed weren't about clever code. They came from bad source data, missing checks or pipelines that failed quietly. So I build validation, monitoring and retries in from the start, not as a patch later.

Right now I'm growing in **Microsoft Fabric, Azure and lakehouse design**, and I'm preparing for **DP-700** and **DP-600**.

---

## 💼 Experience at a glance

| Where | Role | What I did |
|---|---|---|
| **Data for Good** | Data Consultant / Data Modeler (2026-now) | Data modeling and analysis for non-profit clients. For Atira Women's Resource Society, I'm turning manual incident-report forms into a Microsoft Fabric data model, with source-to-target mapping, data quality rules and Power Apps forms, and planning Power BI reporting on top. For ICTMD, I analyzed a Drupal and CiviCRM environment and delivered prioritized requirements to leadership. |
| **O2E Brands** | Data Engineer (2021-2024) | Built Python + Airflow pipelines into Redshift from Salesforce, Google Analytics, PureCloud and Invoca. Added data quality checks, monitoring and retries that cut pipeline failures by about **40%** and API failures by about **70%**. Tuned Redshift SQL for about **60%** faster queries. |
| **Vancouver Coastal Health** | Healthcare ETL Developer (2019-2021) | Built SSIS and T-SQL pipelines for patient, census and lab data. Developed Denodo views to unify clinical systems. Worked on Oracle to SQL Server migration, plus validation and reconciliation. |
| **Georgia Main Food Group** | Junior BI Developer (2017-2019) | Built SSIS pipelines from POS and legacy sources into a SQL Server warehouse, designed star schemas, and built 50+ SSRS and Power BI reports. |

---

## 🛠 Tech stack

**Production experience**
<p>
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/T--SQL-CC2927?style=flat" alt="T-SQL">
  <img src="https://img.shields.io/badge/SSIS-CC2927?style=flat" alt="SSIS">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white" alt="Airflow">
  <img src="https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?style=flat&logo=amazonredshift&logoColor=white" alt="Redshift">
  <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=flat&logo=amazons3&logoColor=white" alt="AWS S3">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Denodo-00A1E0?style=flat" alt="Denodo">
</p>

**Cloud and lakehouse projects**
<p>
  <img src="https://img.shields.io/badge/Microsoft%20Fabric-742774?style=flat&logo=microsoft&logoColor=white" alt="Microsoft Fabric">
  <img src="https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat&logo=microsoftazure&logoColor=white" alt="Azure Data Factory">
  <img src="https://img.shields.io/badge/Azure%20SQL-0078D4?style=flat&logo=microsoftazure&logoColor=white" alt="Azure SQL">
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white" alt="Databricks">
  <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat" alt="Delta Lake">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
</p>

**Learning now:** PySpark · Spark · KQL · dbt · Snowflake

**How I work:** Medallion architecture · Dimensional modeling · Source-to-target mapping · Data validation and reconciliation · Monitoring and retries

---

## 📌 Featured projects

### 🌐 [Global Retail Lakehouse on Microsoft Fabric](https://github.com/bashoori/Global-Retail-Lakehouse-on-Microsoft-Fabric)
A Bronze / Silver / Gold lakehouse for a fictional multi-country retailer.
- Metadata-driven loads with separate backfill and incremental paths
- Silver layer for quality checks, schema alignment, currency and time zone handling
- Gold models for sales, inventory and customers, ready for Power BI
> **Stack:** Microsoft Fabric · OneLake · Pipelines · Spark notebooks · Delta Lake · Power BI

### 🚆 [Transit Data Warehouse (GTFS)](https://github.com/bashoori/transit_data_warehouse)
An end-to-end warehouse built on a real public transit GTFS feed.
- Bronze, Silver and Gold layers, with assertion tests for keys, nulls and duplicates
- Handles GTFS times past 24:00 and expands service calendars into a date dimension
- Star schema with route, stop, trip and date dimensions and trip-level facts
> **Stack:** Python · Medallion architecture · Dimensional modeling · Data quality tests

### ⚙️ [ETL Pipeline with Airflow, Docker and AWS](https://github.com/bashoori/cloud-etl-modernization-airflow-aws)
A containerized Airflow pipeline that ingests JSON, transforms it in Python and loads it to a Redshift-style target.
- A small demo of the Airflow patterns I worked with at O2E
- Runs locally with Docker and Codespaces
> **Stack:** Apache Airflow · Python · Docker · AWS S3 / Redshift (emulated)

### 🔬 [Databricks Lakehouse Pipeline](https://github.com/bashoori/databricks-lakehouse-pipeline)
A medallion pipeline on Azure Databricks for retail-style data.
- Incremental MERGE into Delta tables, cleansing and validation in Silver
- Daily and category-level sales aggregates in Gold
> **Stack:** Azure Databricks · Delta Lake · Unity Catalog · PySpark · SQL

### 🏥 [Healthcare FHIR Data Pipeline](https://github.com/bashoori/healthcare-FHIR-data-pipeline)
Parses FHIR JSON bundles from synthetic patient data into tables, with a small dashboard on top.
- Patient, condition, encounter and observation tables in SQLite
- Streamlit dashboard with filters
> **Stack:** Python · pandas · SQLite · Streamlit · Synthea (synthetic data)

### 📊 [Data Science Projects](https://github.com/bashoori/Data-Science-Projects-Springboard)
My Springboard Data Science work: hypothesis testing, machine learning, SQL and EDA, with two capstones.
> **Stack:** Python · Jupyter · pandas · scikit-learn · SciPy

---

## 🎓 Certifications

- ✅ Microsoft Certified: Azure Data Fundamentals (**DP-900**)
- ✅ Databricks Lakehouse Fundamentals
- ✅ Databricks Generative AI Fundamentals
- ✅ Analyzing Data with Power BI (Microsoft Certificate of Achievement)
- ✅ Scrum Fundamentals Certified (SFC)
- 📘 Preparing for: **DP-700** (Fabric Data Engineer) and **DP-600** (Fabric Analytics Engineer)

---

## 📣 Sharing what I learn

**Note:** - 🎥 **[Data with Bita](https://www.youtube.com/@bitadigitalhub)** on YouTube: Microsoft Fabric, Azure, SQL and real-world data engineering scenarios
- 📝 **[bitadigitalhub.com](https://bitadigitalhub.com)**: free DP-700 study notes
- 💬 **[Data Engineers Club](https://t.me/dataengineers_club)** on Telegram: a community for learning data engineering together
- 🎓 A DP-900 practice test course on Udemy

---

## 🔎 What I'm looking for

**Data Engineer, ETL Developer or Analytics Engineer** roles, especially:
- Microsoft environments (SQL Server, Azure, Fabric)
- Teams modernizing their data platform or moving to a lakehouse
- Healthcare, public sector and community-focused organizations

📍 Vancouver area, BC · Open to hybrid, on-site, remote (Canada) and contract work

<p align="center"><sub><em>Reliable data comes from good design, not from fixing reports afterwards.</em></sub></p>
