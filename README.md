# 🛍️ Customer Segmentation using K-Means Clustering (from Scratch)

This project demonstrates how to implement the **K-Means clustering algorithm from scratch** in Python and apply it to **Mall Customer Data** for customer segmentation. The goal is to group customers based on similar behavior or characteristics to better understand and target them.

## 📘 Project Overview

K-Means is an unsupervised machine learning algorithm used for clustering data into groups based on feature similarity. This project includes:

- Manual implementation of K-Means without using libraries like `sklearn`
- Application to a real-world dataset: Mall Customer Segmentation
- Visual representation of clusters to interpret customer groups

## 📁 Files Included

- `Customer_Segmentation_using_K_Means_Clustering.ipynb` – Jupyter Notebook containing:
  - Implementation of K-Means algorithm from scratch
  - Data preprocessing and visualization
  - Clustering results and insights

## 🔧 Technologies Used

- **Python 3**
- **NumPy** – for numerical operations
- **Matplotlib / Seaborn** – for data visualization
- **Pandas** – for dataset handling

## 📊 Dataset

The **Mall Customer Dataset** typically includes features such as:

- CustomerID
- Age
- Annual Income (k$)
- Spending Score (1–100)

The dataset can be found on [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial) or similar sources.

## 📌 Key Features

- Custom K-Means clustering implementation (initialization, centroid updates, convergence)
- Euclidean distance-based assignment
- Cluster visualization using 2D scatter plots
- Elbow method to determine optimal k

## 📈 Sample Output

- Clusters of customers based on spending habits and income
- Insights into high-value vs low-engagement customer groups

## 📚 Future Enhancements

- Compare with sklearn’s KMeans for validation
- Add support for more distance metrics
- Automate selection of optimal k using Silhouette Score
