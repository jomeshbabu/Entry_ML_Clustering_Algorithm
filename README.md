# Entry_ML_Clustering_Algorithm
1. Loading and Preprocessing
Task: Load the Iris dataset, drop the "species" column, and display the first few rows of the data.
Libraries Used: pandas, matplotlib, seaborn, sklearn.datasets.
2. KMeans Clustering
Description: Briefly explains KMeans clustering:
Divides data into k clusters by minimizing the within-cluster sum of squares (WCSS).
Iteratively assigns data points to the nearest centroid and updates the centroids.
Application:
Used the Elbow Method to determine the optimal number of clusters (k).
Performed KMeans clustering with k=3 on the Iris dataset.
Visualized the clusters in 2D using PCA (Principal Component Analysis).
3. Hierarchical Clustering
Description: Explains Hierarchical clustering:
Builds a dendrogram by merging or splitting clusters iteratively.
Agglomerative clustering starts with individual points and merges them based on similarity.
Application:
Generated a dendrogram using the Ward linkage method.
Applied Agglomerative Clustering with k=3 clusters.
Visualized the resulting clusters in 2D using PCA.
Visualizations
KMeans:
Displayed a 2D PCA plot with clusters color-coded.
Used the Elbow Method graph to justify the number of clusters.
Hierarchical Clustering:
Showed a dendrogram for visualizing cluster hierarchy.
Displayed PCA-based scatterplots for cluster visualization.
Strengths
Comprehensive preprocessing and clustering workflow.
Clear descriptions of clustering methods.
