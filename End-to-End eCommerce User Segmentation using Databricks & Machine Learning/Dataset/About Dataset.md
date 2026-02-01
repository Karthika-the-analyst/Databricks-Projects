# 📊 Dataset – eCommerce Behavior Data

## 📌 Dataset Overview
This project uses the **eCommerce Behavior Data from a Multi-Category Store**, which contains detailed user interaction events collected from a large online retail platform.

The dataset is widely used for:
- User behavior analysis
- Recommendation systems
- Customer segmentation
- Funnel and conversion analysis

---

## 🔗 Dataset Source (Kaggle)
**Dataset Name:** eCommerce behavior data from multi category store  
**Source:** Kaggle  

👉 Dataset Link:  
https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

> ⚠️ Due to large file size (multiple GBs), the dataset is **not uploaded to GitHub**.

---

## 🗂 Data Description
- Time period: **October 2019 – April 2020**
- Data type: **Event-level user behavior**
- Each row represents a user event on the eCommerce website

### 🔹 Event Types
- `view` – User viewed a product
- `cart` – User added product to cart
- `remove_from_cart` – User removed product from cart
- `purchase` – User purchased a product

---

## 📄 Important Columns
| Column Name       | Description |
|------------------|-------------|
| event_time       | Timestamp of the event (UTC) |
| event_type       | Type of user action |
| product_id       | Unique product identifier |
| category_id      | Product category ID |
| category_code    | Product category name |
| brand            | Product brand (can be null) |
| price            | Product price |
| user_id          | Permanent user ID |
| user_session     | Session-level user identifier |

---

## ☁️ Upload Dataset to AWS S3

### 🔗 Load Data into Databricks using External Location
- External Locations are created using **Unity Catalog**
- AWS S3 bucket is securely accessed from Databricks
- Raw data is ingested into the **Bronze layer** of the Medallion Architecture

---

## 🎥 Video Tutorial
Step-by-step tutorial covering:
- Downloading the dataset from Kaggle
- Uploading large files to AWS S3
- Creating External Location in Databricks
- Loading data into Databricks Bronze layer

👉 Watch here:  
[https://www.youtube.com/@YOUR-CHANNEL-NAME](https://youtu.be/761SQ9Hxbic?si=TRXr80pctCikV_ni)

---

## 📌 Notes
- Dataset size is large (multiple `.csv.gz` files)
- Recommended to process data **month-wise**
- External Locations ensure **secure and scalable** access to cloud data

---

## 🙏 Credits
- Dataset provided by **REES46 Marketing Platform**
- Hosted and shared via **Kaggle**
