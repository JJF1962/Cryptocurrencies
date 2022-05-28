# Cryptocurrencies Analysis

## Objective
It was learned the use of  machine learning applying unsupervised algorithms, exploring data when we're not sure what we're looking for. therefore we are in the posicion to analyze data without a clear output in mind. This module is very challenging a we were expose to a different way of thinking.
It was used The K-means algorithm, the main unsupervised algorithm that groups similar data into clusters. We built on this by speeding up the process using principal component analysis (PCA), which employs many different features, in summary we learned to: 
* Describe the differences between supervised and unsupervised learning, including real-world examples of each.
* Preprocess data for unsupervised learning.
* Cluster data using the K-means algorithm.
* Determine the best number of centroids for K-means using the elbow curve.
* Use PCA to limit features and speed up the model.

Tools used: Jupyter Notebook
Libraries: Pandas, hvplot, path import Path, plotly.express as px, sklearn, StandardScaler, MinMaxScaler, PCA, sklearn.cluster, KMeans
Language: Phyton
Challenges: Install hvplot, plotly and sklearn

## Results

The following actions and information were used to develop the challenge 18:
### Load the crypto_data.csv dataset

![this is an image](https://github.com/JJF1962/Cryptocurrencies/blob/main/images/Deliverable%201%20Load%20the%20crypto_data.csv%20dataset.PNG)

## The data was preprocessed for PCA
In order to proprocess the crypto_data. csv for PCA, we coded to keep all the cryptocurrencies that are being traded, keep all the cryptocurrencies that have a working algorithm; It was removed the IDTrading Column, because content text data, no posibile to interpretate using unsupervised algorithms, after that, it were removed all the cells that contain at least one (1) null value, keeping the rows were coins were mined, aditionally it was created a new dataframe that holds only the cryptocurrencies names. and in the following codes it was drop the 'CoinName' column since it's not going to be used on the clustering algorithm, used the get_dummies() to create variables for text features, and fianlly we standarize the data with StandardScaler as shown below:



•	Data Dimensions were reduced using PCA
•	Cryptocurrency Clusters were developed using K-means
•	Visualizations were developed
3-D Scatter Plot with Hover Data Information

