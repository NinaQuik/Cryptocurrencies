# Cryptocurrencies

## Project Overview

This project uses unsupervised machine learning to create a classification system for tradable cryptocurrencies. The [data](/Resources/crypto_data.csv) was retrieved from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist).

The following steps were taken during the analysis:

 - Preprocessing the data for Principal Component Analysis
- Reducing Data Dimensions using Principal Component Analysis (PCA)
- Cluster cryptocurrencies using K-means algorithm from sklearn
- Visualizing the results with 2d and 3d scatter plots using plotly and hvplot

## Results
After removing null values, filtering the data for only mined cryptocurrencies, and using get_dummies() to create variables for text features, the cleaned data yielded 532 tradable cryptocurrencies.

The next step is determining how many clusters should be used in the analysis.  An elbow curve shows that a decrease in inertia begins to slow are around 4.  Therefore K=4 was used in the model.

![ElbowCurve](/Resources/ElbowCurve.png)


