# Cryptocurrencies

## Overview
For this challenge we are using unsupervised machine learning to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for investment purposes. The challenge consists of 4 deliverables:
- Preprocessing the Data for PCA
- Reducing Data Dimensions Using PCA
- Clustering Cryptocurrencies Using K-means
- Visualizing Cryptocurrencies Results

## Results

### Clustering Cryptocurrencies using K-Means
Based on the elbow curve the best k value appears to be 4, so we will use an output of 4 clusters to group the cryptocurrencies

<img width="752" alt="Screen Shot 2022-01-09 at 9 44 52 AM" src="https://user-images.githubusercontent.com/89098766/148687293-131a368c-e3c9-4637-a00d-39a6a337b7b8.png">


### 3D Scatter Plot with Clusters

<img width="795" alt="Screen Shot 2022-01-09 at 9 48 29 AM" src="https://user-images.githubusercontent.com/89098766/148687388-1aa1e6d5-e253-4561-b071-08c371dd2772.png">

This 3-D scatter plot was created using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components. The scatter plot visualizes the classifications of the cryptocurrencies.

### Tradable Table
This table allows us to sort and select cryptocurrencies by class. We can also start to see the majority of cryptocurrencies fall into class 0 and 1, with a few in class 2 and 3.

<img width="774" alt="Screen Shot 2022-01-09 at 9 51 55 AM" src="https://user-images.githubusercontent.com/89098766/148687549-c8d6dee2-b372-451b-87df-5a14f2d2071a.png">

### 2D Scatter Plot with TotalCoinsMined and TotalCoinSupply

<img width="800" alt="Screen Shot 2022-01-09 at 9 55 03 AM" src="https://user-images.githubusercontent.com/89098766/148687657-c931e857-632f-421b-9871-3143ad666d04.png">


## Summary
After cleaning the data, we were able to identify 532 tradable cryptocurrencies, then using unsupervised machine learning we were able to classify them based on their similarities. Finally we were able to visualize the classifications on 2D and 3D plots. Now that the cryptocurriences have been placed into classifications we can analyze them and better make informed investment decisions based on class. 
