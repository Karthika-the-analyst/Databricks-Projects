# 🤖 Machine Learning

## ❓ What is Machine Learning?
Machine Learning (ML) is a subset of Artificial Intelligence that allows systems to **learn patterns from data and make decisions or predictions without being explicitly programmed**.

Instead of writing rules manually, ML models learn from historical data.

---

## 📚 Types of Machine Learning
There are three main types of Machine Learning:

### 1️⃣ Supervised Learning
- Uses labeled data
- Examples: classification, regression  
- Eg: Predicting sales, spam detection

### 2️⃣ Unsupervised Learning
- Uses unlabeled data
- Finds hidden patterns or groups
- Examples: clustering, dimensionality reduction

### 3️⃣ Reinforcement Learning
- Learns through rewards and penalties
- Common in robotics and gaming

---

## 🔍 What Type of ML is Used in This Project?
This project uses **Unsupervised Learning**.

### Algorithm Used
- **K-Means Clustering**

### Why K-Means?
- Simple and scalable
- Works well for large datasets
- Ideal for **user segmentation** problems

---

## 🛒 Machine Learning in This Project
### Project Goal
To segment eCommerce users based on their **behavior and engagement patterns**.

### ML Workflow
- Feature engineering from Gold layer data
- Standardization of features
- Apply K-Means clustering
- Evaluate clusters
- Track experiments using **MLflow**

### Output
The model groups users into meaningful segments such as:
- Browsers
- Engaged Users
- High-Value Customers

These segments are used for **business insights and dashboards**.

---

## 📂 Project Structure
This folder contains the Machine Learning notebook:

Machine Learning/
┗ 📄 ML_user_segmentation.ipynb


---

## 📌 Notes
- Model training is done on curated **Gold layer data**
- MLflow is used for experiment tracking and reproducibility
- The output clusters are consumed by dashboards



