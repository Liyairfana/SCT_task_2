# 🛍️ Mall Customer Segmentation using K-Means

This project performs customer segmentation using the **K-Means clustering algorithm** on the **Mall Customer dataset**. The goal is to group customers based on their demographic and spending behavior to help businesses target the right customers with the right products.

## 📂 Dataset
The dataset contains information about:
- **CustomerID**
- **Gender**
- **Age**
- **Annual Income (k$)**
- **Spending Score (1–100)**

## 🧠 Techniques Used
- Data Preprocessing (Label Encoding for Gender)
- Elbow Method to find optimal clusters
- K-Means Clustering
- Cluster Visualization using `matplotlib`

## 📊 Features for Clustering
- Gender (encoded)
- Age
- Annual Income
- Spending Score

## 📌 Output
- Elbow Curve to determine optimal `k`
- Scatter plot showing customer segments

pandas
matplotlib
scikit-learn
