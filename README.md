# 🛍️ Customer Segmentation using K-Means Clustering

This project applies unsupervised machine learning (K-Means Clustering) to segment retail store customers based on their annual income and spending behavior. These insights can help businesses tailor marketing strategies and personalize customer experiences.



## 📌 Project Overview

- **Algorithm Used**: K-Means Clustering
- **Goal**: Group customers into distinct clusters for targeted marketing
- **Dataset**: Mall Customers Dataset
- **Key Features Used**:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`



# 🧠 Project Workflow

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



## 📊 Clustering Output Sample

| CustomerID | Income (k$) | Spending Score | Cluster |
|------------|-------------|----------------|---------|
| 1          | 15          | 39             | 1       |
| 2          | 15          | 81             | 0       |
| ...        | ...         | ...            | ...     |



## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: 
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `seaborn` 



## 📁 Folder Structure
.
├── customer_segmentation.py # Main script
├── Mall_Customers.csv # Dataset
├── README.md # Project documentation



## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans


#📈 How It Works
Load and clean data
Visualize distributions (age, income, spending)           
Use the Elbow Method to determine optimal number of clusters
Apply K-Means clustering on selected features (e.g., Annual Income & Spending Score)
Visualize clusters using scatter plots


#📊 Sample Output
📌 Elbow Method Plot
Helps identify the optimal number of clusters (k) using Within-Cluster-Sum-of-Squares (WCSS).
🎯 Cluster Visualization (2D)
Each color represents a customer segment (e.g., High income / High spenders, etc.)


#💡 Future Improvements
Use 3D plots for richer cluster insights
Try other clustering methods (DBSCAN, Hierarchical)
Build a web dashboard using Streamlit
Integrate customer labels into business intelligence tools

#👨‍💻 Author
Sanju Reddy
Machine Learning Intern
This project is part of my Prodigy InfoTech Internship


