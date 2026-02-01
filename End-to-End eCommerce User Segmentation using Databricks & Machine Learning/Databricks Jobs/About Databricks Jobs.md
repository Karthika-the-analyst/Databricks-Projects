# ⏰ Databricks Jobs

## 📌 What are Databricks Jobs?
Databricks Jobs are used to **automate and orchestrate workflows** in Databricks.  
They allow notebooks, SQL queries, and ML tasks to run in a **scheduled, reliable, and repeatable** manner.

---

## ❓ Why Databricks Jobs in This Project?
Databricks Jobs are used to:
- Automate the end-to-end data pipeline
- Ensure consistent execution of notebooks
- Support scheduled and production-like workflows
- Reduce manual intervention

---

## 🏗 Job Workflow in This Project
The Databricks Job orchestrates the complete pipeline in the following order:


Bronze Ingestion

↓

Silver Transformation

↓

Gold Aggregation


Each step runs only after the previous step completes successfully.

---

## 🧩 Job Components
The job includes the following tasks:
- **Bronze Notebook** – Raw data ingestion from AWS S3
- **Silver Notebook** – Data cleaning and transformation
- **Gold Notebook** – Business-level aggregations

---

## ⏱ Scheduling
- Jobs can be scheduled to run at specific intervals
- Supports on-demand and automated execution
- Enables incremental and scalable processing

---

## 📂 Files in This Folder

databricks_jobs/
┣ 📄 About Databricks Jobs.md

┗ 🖼 job_workflow.png

- `job_workflow.png` shows the visual workflow of the Databricks Job pipeline

---

## 🚀 Benefits
- End-to-end pipeline automation
- Improved reliability and consistency
- Production-ready workflow design
- Easy monitoring and retry on failure

---

## 📌 Notes
- Jobs are configured using Databricks UI
- Supports retries, alerts, and cluster reuse
- Designed to align with Medallion Architecture
