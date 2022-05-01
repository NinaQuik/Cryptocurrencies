# Cryptocurrencies

## Project Overview

This project uses unsupervised machine learning to create a classification system for tradable cryptocurrencies. The [data](/Resources/crypto_data.csv) was retrieved from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist).

The following steps were taken during the analysis:

 - Preprocessing the data for Principal Component Analysis
- Reducing Data Dimensions using Principal Component Analysis (PCA)
- Cluster cryptocurrencies using K-means algorithm from sklearn
- Visualizing the results with 2d and 3d scatter plots using plotly and hvplot

