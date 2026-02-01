# 🛒 End-to-End eCommerce User Segmentation using Databricks & Machine Learning

## 📌 Project Overview
This project demonstrates an end-to-end **data engineering and machine learning pipeline** built using **Databricks** for an eCommerce use case.

The objective is to analyze **user behavior**, perform **user segmentation using machine learning**, and generate **actionable business insights** through dashboards.

The solution follows **Medallion Architecture (Bronze → Silver → Gold)**, uses **AWS S3** for data storage, and **MLflow** for model tracking and experimentation.

---

## 📊 Dataset
- Public eCommerce behavioral dataset
- Contains user interactions such as:
  - Product views
  - Clicks
  - Purchases
  - Session-level activity
- Raw data stored in **AWS S3**
- Loaded into Databricks using **External Locations**

Detailed dataset information, source link, and AWS upload steps are available in:



---

## 🧱 Medallion Architecture

### 🟤 Bronze Layer
- Raw data ingestion from AWS S3
- Schema enforcement
- Stored as Delta tables

### ⚪ Silver Layer
- Data cleaning and transformation
- Deduplication and null handling
- Feature-ready structured data

### 🟡 Gold Layer
- Aggregated business metrics
- User-level KPIs
- Optimized for dashboards and machine learning

---

## 🤖 Machine Learning Used
- **Algorithm:** K-Means Clustering
- **Goal:** User segmentation based on behavior and engagement
- **Feature Engineering:**
  - Session counts
  - Engagement metrics
  - Purchase behavior
- **MLflow:**
  - Experiment tracking
  - Model versioning
  - Metric comparison

**Output User Segments:**
- Browsers
- Engaged Users
- High-Value Customers

---

## ⏰ Databricks Jobs
- End-to-end pipeline orchestration using **Databricks Jobs**
- Automates:
  - Bronze → Silver → Gold transformations
  - Machine learning execution
- Supports scheduled and repeatable runs

Job configuration and workflow images are available in the:


---

## 📈 Dashboards
Interactive dashboards built using **Databricks SQL** on the Gold layer.

Dashboards include:
- User segment distribution
- Engagement metrics by segment
- Business insights and recommendations

Dashboard images and insights are available in:

---

## 🙏 Acknowledgements
Special thanks to:
- **Codebasics**
- **Indian Data Club (IDC)**
- **Databricks**

for providing learning resources and hands-on project opportunities.

---

## 🔗 Connect With Me
- **LinkedIn:** https://www.linkedin.com/in/YOUR-LINK
- **YouTube:** https://www.youtube.com/@YOUR-CHANNEL


