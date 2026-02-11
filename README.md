# K-means-Countries-Development-Status-Project
This project implements a K-Means Clustering algorithm to perform unsupervised machine learning. This project focuses on identifying underlying patterns or groupings within a dataset to derive actionable insights. K-Means Clustering is used to group countries based on socio-economic and health factors to determine the development status of the countries. 

## Methodology
1. Data Preprocessing & Exploration
•	Verified no missing values in the dataset.
•	Dropped non-numeric features (country column) for the clustering algorithm.
•	Conducted exploratory data analysis (EDA) using Seaborn Heatmaps and Scatter Plots to identify correlations and insights in the dataset. 
2. Feature Scaling
Since K-Means is a distance-based algorithm, all features were normalized using MinMaxScaler to ensure that high-magnitude variables (like income) didn't overshadow smaller variables (like total_fer).
3. Finding Optimal Clusters (K)
Two primary methods were utilized to determine the optimal number of clusters:
•	The Elbow Method: The Elbow method is applied by plotting the within-cluster sum of squares (WCSS) against different values of K. 
•	Silhouette Score: The silhouette score method is used to measure how well-defined the clusters are.
4. Implementing K-Means Clustering
The K-means algorithm is implemented using the scikit-learn library and the selected optimal number of clusters (k) to cluster the countries based on the socio-economic and health features.
5. Model Evaluation
Silhouette Score: The silhouette score is calculated to assess the quality of the clustering results. 
Cluster Visualisation: Visualizing the clusters to interpret the results.
