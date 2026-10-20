# 🍷 Wine Clustering Project

Unsupervised machine learning project using the Wine Dataset for Clustering.

## Project Goal
Group wine samples according to their chemical characteristics without using a target variable.

## Dataset
- 178 wine samples
- 13 numerical features
- 0 missing values
- 0 duplicate rows
- Source: Kaggle – Wine Dataset for Clustering by Harry Wang

## Methods
- Exploratory Data Analysis
- StandardScaler
- Elbow Method
- Silhouette Score
- K-Means Clustering
- PCA 2D visualization
- Cluster profile heatmap
- Hierarchical Clustering comparison
- Interactive 3D PCA visualization

## Main Result
- Selected number of clusters: 3
- K-Means Silhouette Score: ~0.285
- PCA 2D explained variance: ~55%

## Cluster Interpretation
- Cluster 0: Light & Balanced
- Cluster 1: Intense & Acidic
- Cluster 2: Rich & Phenolic

These labels are descriptive interpretations, not official wine classes or quality ratings.

## Files
- `Wine_Clustering_Project.ipynb` – complete analysis
- `wine-clustering.csv` – original dataset
- `wine_clustered.csv` – generated dataset with cluster labels
