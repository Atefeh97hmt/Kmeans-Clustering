# K-Means Clustering
This repository contains a Python script for performing K-means clustering on a dataset of customers. K-Means clustering is an unsupervised machine learning algorithm that partitions data points into distinct groups (clusters) based on their similarity.

## Prerequisites
- Python 3
- Libraries: NumPy, Matplotlib, Pandas, scikit-learn

## Getting Started
1.	Clone the repository:
- git clone https://github.com/Atefeh97hmt/Kmeans-Clustering
- cd Kmeans-Clustering
1.	Install the required libraries:
- pip install numpy 
- pip install matplotlib 
- pip install pandas 
- pip install scikit-learn
2.	Download the dataset (`Customers.csv`) and place it in the root directory.
3.	Run the script:
- python kmeans_clustering.py

## Description
- Importing Libraries: The necessary libraries (NumPy, Matplotlib, Pandas) are imported.
- Importing Dataset: The customer dataset (`Customers.csv`) is loaded, and the relevant features are selected.
- Elbow Method: The script uses the elbow method to determine the optimal number of clusters (k) for K-Means clustering.
- K-Means Clustering: The K-Means algorithm is applied to the dataset with the optimal number of clusters found using the elbow method.
- Visualizing Clusters: The script visualizes the clusters by plotting the data points and cluster centroids using Matplotlib.

## Results
The script generates a plot showing the clusters of customers based on their annual income and spending score. Each cluster is assigned a different color, and centroids are marked with a black cross.

## Customization
You can customize the script by adjusting the number of clusters (`n_clusters`) and other parameters in the KMeans class.



- Author: Atefeh Hemmati
- Contact: Hemmati.atefeh97@gmail.com

