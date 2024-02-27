# CryptoClustering

Cryptocurrency Clustering Assignment

Overview
This assignment involves normalizing cryptocurrency data, finding the optimal number of clusters (k), and clustering the data using K-means. You'll work with both the original normalized data and data reduced via PCA (Principal Component Analysis).

Steps:
Normalize Data: Use StandardScaler() to normalize your CSV data. Create a DataFrame for the scaled data, using "coin_id" as the index.

Find Optimal k: Use the elbow method on both the original scaled data and PCA-reduced data to find the best k value. Plot the inertia values to help identify the optimal k.

Cluster Cryptocurrencies:

With the original scaled data, initialize K-means with the best k, fit the model, and predict clusters. Add the predicted clusters to a new column in your data.
Use hvPlot to create a scatter plot with "PC1" and "PC2" axes, coloring points by their clusters and including "coin_id" for identification.
PCA Reduction: Reduce the original scaled data to three principal components. Check the explained variance to understand the importance of each component.

Cluster Using PCA Data: Repeat the clustering process with PCA-reduced data. Determine if the optimal k value changes with PCA data. Visualize the clusters using a scatter plot with "price_change_percentage_24h" and "price_change_percentage_7d" as axes.

Goals:
Understand the effect of feature reduction on clustering.
Learn to identify the optimal number of clusters using the elbow method.
Experience with K-means clustering on both full-dimensional and reduced-dimensional data.