# Cryptocurrency Clustering with K-Means and PCA

## Overview
This project explores clustering cryptocurrencies using K-Means and Principal Component Analysis (PCA) to identify meaningful groupings based on market data. The goal is to analyze and visualize trends in the crypto market by applying machine learning techniques to real-world financial data.

## Problem Statement
With thousands of cryptocurrencies in the market, it is challenging to categorize them based on their performance metrics. This project aims to use clustering algorithms to group similar cryptocurrencies, helping analysts and investors gain insights into market trends.

## Data
The dataset used in this project is `crypto_market_data.csv`, which contains various cryptocurrency attributes, including price changes over different time frames. The data was preprocessed and normalized using `StandardScaler` from Scikit-learn.

## Methodology
1. **Data Preprocessing**  
   - Load the dataset into a Pandas DataFrame.  
   - Normalize the data using `StandardScaler()`.  
   - Perform exploratory data analysis to understand key features.

2. **K-Means Clustering**  
   - Compute the inertia values for different values of `k` to determine the optimal number of clusters using the Elbow Method.  
   - Cluster the cryptocurrencies based on their performance metrics.

3. **Principal Component Analysis (PCA)**  
   - Reduce the dataset to three principal components while preserving most of the variance.  
   - Perform clustering again using PCA-transformed data and compare the results.

4. **Visualization**  
   - Plot the Elbow curve to determine the best value for `k`.  
   - Create scatter plots to visualize the clustered cryptocurrencies.  
   - Analyze how PCA affects the clustering results.

## Findings
- The optimal number of clusters (`k`) was determined using the Elbow Method. k=4
- PCA helped reduce dimensionality while retaining a significant portion of the dataset's variance.

## Conclusion
Applying K-Means clustering to cryptocurrency market data helps in categorizing assets based on performance. PCA proved useful in simplifying the dataset while maintaining valuable insights. This analysis can serve as a foundation for further research into crypto market trends.

## Resources
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)  
- [Pandas Documentation](https://pandas.pydata.org/)  
- [Matplotlib Documentation](https://matplotlib.org/)
- Class Activities and Slides
- Google
- Open AI
