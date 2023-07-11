# Cryptocurrency Clustering Project

This project involves clustering cryptocurrencies based on their price change percentages using K-Means algorithm and Principal Component Analysis (PCA). The aim is to group similar cryptocurrencies together and gain insights from the clusters.

## Project Overview

The project involves the following main steps:

1. Data Preprocessing: The initial cryptocurrency market data is loaded and preprocessed by removing unnecessary columns and handling missing values. The data is then scaled using StandardScaler to normalize the features.

2. Dimensionality Reduction: Principal Component Analysis (PCA) is applied to reduce the dimensionality of the data and capture the most important features. The explained variance is analyzed to determine the amount of information retained by each principal component.

3. K-Means Clustering: The scaled data or the PCA-transformed data is used for clustering using the K-Means algorithm. The optimal number of clusters is determined by analyzing the Elbow curve, which shows the inertia values for different values of k. The clusters are predicted and added as a new column to the data.

4. Visualization: The clustered cryptocurrencies are visualized using scatter plots, where the x and y axes represent different price change percentages. Each data point is colored according to its cluster label, and the hover functionality displays the corresponding cryptocurrency name.

## Results

The project results include:

- Elbow curve: A plot showing the inertia values for different values of k, helping to identify the optimal number of clusters.
- Clustered Cryptocurrencies: Scatter plots that visualize the clustered cryptocurrencies based on their price change percentages. The colors represent different clusters, and the hover functionality provides the cryptocurrency names.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

