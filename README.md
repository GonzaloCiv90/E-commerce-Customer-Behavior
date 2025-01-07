# E-commerce-Customer-Behavior

Project Overview

This project focuses on analyzing customer behavior in an e-commerce dataset. Through a combination of exploratory data analysis (EDA) and unsupervised learning techniques, we identified patterns and grouped customers into meaningful clusters to derive actionable insights.

Key Steps Undertaken

Dataset Exploration


Analyzed key variables such as age, gender, membership type, total spend, and satisfaction levels.
Identified relationships and patterns between variables using visualizations and statistical summaries.

Preprocessing

Standardized the dataset to ensure uniform scaling for clustering algorithms.
Applied dimensionality reduction using Principal Component Analysis (PCA) for improved algorithm performance.

Clustering Models

Implemented K-Means Clustering using the Elbow Method to determine the optimal number of clusters (k = 7).
Evaluated K-Means using Silhouette Score (0.82).
Applied DBSCAN Clustering, enhancing performance with PCA, achieving a Silhouette Score of 0.80.
Compared clustering results to identify similarities and outliers.

Visualizations

Created scatter plots to visualize customer segmentation based on age, total spend, and other variables.
Highlighted cluster centroids and differences between models for clarity.

Insights and Recommendations

Identified customer demographics and behavior patterns within clusters.
Suggested strategies to target specific customer segments and improve satisfaction levels.

Conclusion

This project demonstrates how data science techniques, such as clustering and PCA, can provide valuable insights into customer behavior. These methods allow businesses to better understand their customer base and implement data-driven decisions.
