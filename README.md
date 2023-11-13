# CryptoClustering
  Module 19 Challenge Homework Assignment - To predict if cryptocurrencies are affected by 24-hour or 7-day price changes using Unsupervised Learning Techniques, such as K-means clustering and Principal Component Analysis (PCA) 
  
    CREATED BY MICHAEL ROBERTS

This repository contains the following:

A. A Resources folder containing the file 'crypto_market_data.csv'. This file contains the data that is loaded into 
the Jupyter file: 'Crypto_Clustering.ipynb' 

B. The jupyter file, included at the top level of this repository, contains all the code to implement the requirements of homework assignment including:

  1. Import the csv file and prepare the data.
  2. Scale the data using StandardScaler.
  3. Find the best value for k using the elbow method.
  4. Cluster cryptocurrencies with K-means using the original scaled data.
  5. Perform PCA to reduce the features to three principal components.
  6. Find the best value for k using the PCA data.
  7. Cluster cryptocurrencies with K-means using the PCA data.
  8. Visualize and compare the results of Elbow line charts and group cluster scatter plot charts using hvPlot.



