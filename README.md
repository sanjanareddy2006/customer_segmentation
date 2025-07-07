# 🛍️ Customer Segmentation using K-Means Clustering

This project applies unsupervised machine learning (K-Means Clustering) to segment retail store customers based on their annual income and spending behavior. These insights can help businesses tailor marketing strategies and personalize customer experiences.

---

## 📌 Project Overview

- **Algorithm Used**: K-Means Clustering
- **Goal**: Group customers into distinct clusters for targeted marketing
- **Dataset**: Mall Customers Dataset
- **Key Features Used**:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 Project Workflow

1. **Data Preprocessing**
   - Load and clean dataset
   - Feature scaling with StandardScaler

2. **Finding Optimal Clusters**
   - Elbow Method
   - Silhouette Score

3. **K-Means Clustering**
   - Fit KMeans with optimal K
   - Predict cluster labels

4. **Visualization**
   - Plot Elbow graph
   - Scatter plot of customer segments

5. **Export Results**
   - Save `clustered_customers.csv` with cluster labels

---

## 📊 Clustering Output Sample

| CustomerID | Income (k$) | Spending Score | Cluster |
|------------|-------------|----------------|---------|
| 1          | 15          | 39             | 1       |
| 2          | 15          | 81             | 0       |
| ...        | ...         | ...            | ...     |

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: 
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `seaborn` *(optional)*

---

## 📁 Folder Structure

