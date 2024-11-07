# CryptoClustering
![https://cdn-images-1.medium.com/max/800/0*-IdEXvr_Es1WSpRn](https://cdn-images-1.medium.com/max/800/0*-IdEXvr_Es1WSpRn)

This repository contains the solution for the Module 19 Challenge on clustering cryptocurrencies using unsupervised learning techniques, specifically K-Means and Principal Component Analysis (PCA). In this challenge, we work with cryptocurrency data to analyze how 24-hour and 7-day price changes affect different cryptocurrencies.

Challenge Overview
------------------------------
The goal of this project is to:

1. Prepare the data for clustering by normalizing it using the StandardScaler.

2. Find the optimal number of clusters (k) using the elbow method on both the original scaled data and the PCA-reduced data.

3. Cluster cryptocurrencies using the K-Means algorithm.

4. Visualize the clusters in a scatter plot using hvPlot.

5. Optimize the clusters by reducing the data to principal components (PCA) and repeating the clustering process.

6. Compare the clustering results based on original data vs PCA-reduced data.

Steps
--------------------------------------
1. Prepare the Data
   
    * Normalize Data: Use the StandardScaler module from scikit-learn to scale the data.

2. Find the Best Value for k Using the Original Scaled Data
   
    * Elbow Method:Visually inspect the curve to determine the optimal k-value.

3. Cluster Cryptocurrencies with K-means Using the Original Scaled Data

4. Optimize Clusters with Principal Component Analysis (PCA)
  
    * Perform PCA: Reduce the original data to three principal components.

5. Find the Best Value for k Using the PCA Data

6. Cluster Cryptocurrencies with K-means Using the PCA Data

Files
-----------------------------------------------------------------------
crypto_market_data.csv: The raw dataset containing the cryptocurrency data.

Crypto_Clustering_code.ipynb: The Jupyter Notebook where all steps are implemented, including data preprocessing, clustering, and visualizations.


