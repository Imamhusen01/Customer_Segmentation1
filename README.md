# Customer_Segmentation1
This project demonstrates the segmentation of customers based on their Annual Income and Spending Score using the KMeans clustering algorithm. The optimum number of clusters is determined using the elbow method.
Table of Contents

    Introduction
    Dataset
    Methodology
    Results
    

Introduction

Customer segmentation is a crucial aspect of modern business strategies. It involves dividing a customer base into distinct groups that share similar characteristics. In this project, we use the KMeans clustering algorithm to segment customers based on their Annual Income and Spending Score. The optimal number of clusters is identified using the elbow method.
Dataset

The dataset used in this project contains information about customers' annual income and spending scores. The dataset is structured as follows:

    Annual Income (k$): The annual income of the customer in thousand dollars.
    Spending Score (1-100): The spending score assigned to the customer based on their spending behavior.

Methodology

    Data Preprocessing:
        Load the dataset.
        Check for missing values and handle them if necessary.
        Standardize the data if required.

    Elbow Method:
        Compute the within-cluster sum of squares (WCSS) for different numbers of clusters.
        Plot the WCSS values to identify the elbow point, which indicates the optimal number of clusters.

    KMeans Clustering:
        Apply the KMeans algorithm with the optimal number of clusters.
        Assign cluster labels to each data point.

    Visualization:
        Use Seaborn to visualize the clusters in a scatter plot.

Results

The results of the clustering process are visualized in a scatter plot where each point represents a customer, and the color indicates the cluster to which the customer belongs. The clusters help in identifying distinct groups of customers with similar income and spending patterns.
