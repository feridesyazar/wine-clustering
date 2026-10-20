# 🍷 Wine Clustering Project

Unsupervised Machine Learning project using K-Means, PCA, and Hierarchical Clustering to group wines based on their chemical characteristics.

## Project Goal

Group wine samples according to their chemical characteristics without using a target variable.

## Dataset

- 178 wine samples
- 13 numerical features
- 0 missing values
- 0 duplicate rows
- Source: [Kaggle – Wine Dataset for Clustering by Harry Wang](https://www.kaggle.com/datasets/harrywang/wine-dataset-for-clustering)

## Methods

- Exploratory Data Analysis (EDA)
- StandardScaler
- Elbow Method
- Silhouette Score
- K-Means Clustering
- PCA 2D Visualization
- Cluster Profile Heatmap
- Hierarchical Clustering Comparison
- Interactive 3D PCA Visualization

## Main Results

- **Selected number of clusters:** 3
- **K-Means Silhouette Score:** ~0.285
- **PCA 2D Explained Variance:** ~55%
- **Cluster Separation:** Moderate

## Cluster Interpretation

- **Cluster 0 – Lower Alcohol & Color Intensity**
- **Cluster 1 – High Malic Acid & Color Intensity**
- **Cluster 2 – Higher Alcohol, Phenols & Proline**

These clusters represent different chemical profiles, not official wine classes or quality ratings.

## Conclusion

K-Means successfully identified three interpretable wine clusters based on their chemical composition.

The results show moderate cluster separation, demonstrating how Unsupervised Learning can discover meaningful patterns in wine data.

