# Cryptocurrency Clustering Analysis

## Overview
This project uses principal component analysis (PCA) and K-Means clustering to analyze and visualize the relationships between various cryptocurrencies. The goal is to identify patterns and group similar cryptocurrencies together based on their characteristics.

## Data
- The dataset used in this project contains historical price data for various cryptocurrencies.
- The data is scaled using StandardScaler to ensure equal weighting for all features.

## Methodology
- PCA is applied to reduce the dimensionality of the data and extract the most important features.
- K-Means clustering is used to group the cryptocurrencies into clusters based on their PCA features.
- The number of clusters (K) is determined using the Elbow method.

## Results
- The PCA analysis reveals the most important features contributing to the variability in the data.
- The K-Means clustering assigns each cryptocurrency to a cluster based on their similarities.
- Visualizations (scatter plots) are used to illustrate the clustering results and show the relationships between cryptocurrencies.

## Conclusion
This project demonstrates the application of PCA and K-Means clustering to cryptocurrency data. The results provide insights into the relationships between various cryptocurrencies and identify patterns in the data. The methodology can be applied to other datasets and domains to explore similar relationships and patterns.

## Usage
Run the notebook cells in sequence to reproduce the analysis and visualizations.
Modify the parameters (e.g., number of components, clusters) to explore different scenarios.

## Dependencies
- pandas
- numpy
- scikit-learn
- hvPlot
matplotlib