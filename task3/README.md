# Customer Segmentation using PCA and K-Means Clustering

## Overview

This project performs customer segmentation using an unsupervised machine learning approach. Customer purchasing behavior is analyzed by engineering customer-level features, reducing dimensionality with Principal Component Analysis (PCA), and grouping similar customers using the K-Means clustering algorithm.

The objective is to identify meaningful customer segments that can help businesses improve marketing strategies, customer retention, and personalized recommendations.

---

## Features

- Data Cleaning and Preprocessing
- Customer-Level Feature Engineering
- One-Hot Encoding for Categorical Variables
- Feature Scaling using StandardScaler
- Principal Component Analysis (PCA)
- Elbow Method for Optimal K Selection
- Silhouette Score Evaluation
- Customer Segmentation using K-Means
- 2D and 3D PCA Visualization
- Cluster Profiling and Business Insights

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Workflow

1. Load and preprocess the dataset.
2. Create customer-level aggregated features.
3. Encode categorical variables.
4. Scale numerical features.
5. Apply PCA to reduce 20+ features into 3 principal components.
6. Determine the optimal number of clusters using the Elbow Method and Silhouette Score.
7. Train the K-Means clustering model.
8. Visualize customer clusters.
9. Analyze customer personas and generate business insights.

---

## Results

- Successfully reduced high-dimensional customer data into three principal components.
- Determined the optimal number of clusters using quantitative evaluation.
- Segmented customers into meaningful groups based on purchasing behavior.
- Generated actionable customer personas for business decision-making.

---

## Future Improvements

- Compare K-Means with DBSCAN and Hierarchical Clustering.
- Deploy the project using Streamlit.
- Build an interactive customer analytics dashboard.
- Perform real-time customer segmentation.

---

## Author

Avinash
