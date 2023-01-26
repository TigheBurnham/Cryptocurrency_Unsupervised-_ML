# Cryptocurrency_Unsupervised_ML

## Overview

In this project an investment bank is interested in offering a new cryptocurrency investment portfolio. Based on the volume of crypto currencies that exist we have been tasked with creating a report that groups cryptocurrencies into classification systems. Unsupervised machine learning that utilizes a clustering algorithm was determined to be the best machine learning method to create this type of report because there is no known output. 

This new assignment consists of four technical analysis parts.

Part 1: Preprocessing the Data for PCA
Part 2: Reducing Data Dimensions Using PCA
Part 3: Clustering Cryptocurrencies Using K-means
Part 4: Visualizing Cryptocurrencies Results

## Results

- In order to perform a PCA (principal component analysis) we preprocess the dataset by removing rows with null values, dropping any crypto currencies that were not being traded, and filtering the crypto currencies by their trading volume. 

- After preprocessing the data, the dimensions were reduced to three principal components as shown in the graph below.

<img width="207" alt="pca table" src="https://user-images.githubusercontent.com/112028534/214973596-f47daab8-fe75-439c-a708-c6e7ed2acc23.png">

- Utilizing the K-means algorithm, we created an elbow graph to visually find the best value for K. Based on the graph below the best value appears to be 4.

<img width="527" alt="elbow curve" src="https://user-images.githubusercontent.com/112028534/214971190-05e8c26c-bfbc-45a0-a8fc-28d90cebd274.png">

- Next we used the K-means algorithm to make predictions of the K Clusters and then created a new clustered data frame as shown in the image below.

<img width="617" alt="Clustered_df" src="https://user-images.githubusercontent.com/112028534/214974733-e6b40c7b-efde-4960-9dbc-e196b8d98a66.png">

- For the deliverable we were tasked with creating Visualizations of the Cryptocurrencies.

### 3D Scatter Plot

<img width="599" alt="graph" src="https://user-images.githubusercontent.com/112028534/214971215-2b83d450-22fc-4ea2-891a-18bc0698b533.png">

- The above 3D scatter plot is made up of the 3 PCA components calculated in the 3rd deliverable.

### 2D Scatter Plot

<img width="496" alt="mined" src="https://user-images.githubusercontent.com/112028534/214971256-7fe0353a-095e-4d47-959d-2cac85f92578.png">

- The above 2D scatter plot is also made up of the 3 PCA components calculated in the 3rd deliverable.

## Summary

Outside of clustering cryptocurrencies more research should be conducted into what type of investor these types of investments make sense for. Cryptocurrencies main value derives from their scarcity, outside of the technology that goes into creating virtual currency, its value added to an investor's portfolio appears to be only another form of diversification.  
