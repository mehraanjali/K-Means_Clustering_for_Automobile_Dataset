# K-Means Clustering for Automobile Dataset - Clustering_Based_on_hp and weightlbs of cars

## Overview
This project applies K-Means Clustering, a popular unsupervised machine learning technique, to analyze an automobile dataset. The primary objectives are to determine the optimal number of clusters (K) using the Elbow Method and then perform clustering to group automobiles based on their characteristics. The results are visualized to gain insights into the dataset's underlying structure.

## Description
1. Dataset Import
The project begins by importing an automobile dataset from a CSV file. The dataset includes various attributes such as 'mpg' (miles per gallon), 'cylinders,' 'cubicinches,' 'hp' (horsepower), 'weightlbs' (weight in pounds), 'time-to-60' (acceleration), and 'year' (manufacture year). These attributes represent key features of each automobile.

2. Data Preprocessing
Data preprocessing is essential for ensuring data quality. Null values in the dataset are filled with the mean of their respective columns, ensuring that the dataset is clean and ready for analysis.

3. Determining the Optimal Number of Clusters (K)
To find the optimal number of clusters (K), the Elbow Method is employed. This technique involves running K-Means clustering for a range of K values and plotting the within-cluster sum of squares (WCSS) against the number of clusters. The "elbow point" in the graph helps identify the ideal K value.

4. K-Means Clustering
With the optimal K value determined, K-Means Clustering is applied to group the automobiles into clusters. Each cluster represents a group of similar automobiles based on their attributes.

5. Cluster Centroid Calculation
The centroids (cluster centers) for each cluster are calculated. These centroids represent the typical characteristics of automobiles within each cluster.

6. Visualization
The results are visualized using a scatter plot. Each point in the plot represents an automobile, and the color indicates the cluster to which it belongs. Additionally, the cluster centroids are marked on the plot for easy identification.

## Interpretation
The project's output provides insights into how automobiles can be grouped based on their characteristics. For example, it may reveal clusters of high-performance sports cars, fuel-efficient economy cars, and other groupings. These insights can be valuable for market segmentation and product targeting in the automotive industry.
