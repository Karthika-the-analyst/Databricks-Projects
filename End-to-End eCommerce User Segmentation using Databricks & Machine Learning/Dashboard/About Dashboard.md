# 📈 E-Commerce Business Insights Dashboards

## 📌 Dashboard Overview
These dashboards are built using **Databricks SQL** on top of the **Gold layer** and **Machine Learning outputs**.

They convert raw data and ML results into **clear business insights** that help stakeholders understand:
- Revenue performance
- User behavior
- Product performance
- ML-based user segmentation

The dashboards are divided into two main sections:
- **Business KPIs**
- **ML User Segmentations**

---

## 📊 Business KPIs Dashboard
This dashboard focuses on **overall business performance**.

### 🔹 Key Metrics
- **Total Revenue:** Overall revenue generated across the platform
- **Total Purchases:** Total number of purchase events
- **Total Events:** Total user interactions (views, carts, purchases)

### 🔹 Visualizations
- **Daily Revenue Trend**
  - Shows revenue movement over time (Oct 2019 – Apr 2020)
  - Helps identify peak and low-performance periods

- **Top 10 Products by Revenue**
  - Highlights products contributing the most to revenue
  - Useful for inventory and promotion strategies

- **Top Users by Purchase & Spend**
  - Identifies high-spending and highly active users
  - Useful for loyalty programs and personalization

---

## 🤖 ML User Segmentation Dashboard
This dashboard visualizes the output of the **Machine Learning model**.

### 🔹 User Segments
Users are grouped into three segments:
- **High-Value Loyal Customers**
- **Occasional Buyers**
- **Browsers / Non-Converters**

### 🔹 Visualizations
- **User Count by Segment**
  - Shows distribution of users across segments

- **Average Revenue by Segment**
  - Demonstrates which segment contributes the most revenue
  - Highlights high-value customers despite smaller population

- **Engagement by Segment**
  - Browsers show very high engagement but low conversion
  - Loyal customers show lower engagement count but higher value

---

## 🧠 Key Insights
- A **small percentage of users generate the majority of revenue**
- Browsers / Non-Converters interact heavily but do not convert
- High-Value Loyal Customers contribute maximum revenue with fewer interactions
- Medium / Occasional buyers form the largest user base

---

## 💡 Business Recommendations
Based on dashboard insights:
- Run **personalized campaigns** for high-value loyal customers
- Apply **retargeting strategies** for browsers
- Use discounts or reminders to convert occasional buyers
- Focus marketing spend on **high ROI user segments**

---

dashboards/
┣ 🖼 dashboard.pdf

┗ 📄 About Dashboard.md


---

## 📌 Notes
- Dashboards consume only **Gold layer** data
- User segments are generated using **ML (K-Means clustering)**
- Designed for **performance, clarity, and business decision-making**


## 📂 Files in This Folder

dashboards/
┣ 🖼 dashboard_business_kpis.png

┣ 🖼 dashboard_ml_user_segmentation.png

┗ 📄About Dashboard.md

## 🔗 Dashboard Link
👉 **Databricks SQL Dashboard:**  
[https://<your-databricks-workspace>/sql/dashboards/<dashboard-id>](https://dbc-e2659389-81fe.cloud.databricks.com/dashboardsv3/01f0fc00a37f19d18f546135d0b11859/published?o=7474653933749029)

> Note: Dashboard access may require Databricks workspace permissions.
