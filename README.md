# Customer Segmentation using K-Means Clustering

This project applies K-means clustering to segment customers of a retail store based on their purchase behavior, specifically considering their annual income and spending score. This segmentation helps in identifying distinct customer groups, which can assist in creating targeted marketing strategies.

# Project Overview
In this project, we use the K-means clustering algorithm to group customers based on their purchasing habits. By identifying clusters, we can better understand different customer segments, such as high-income customers with low spending scores, low-income customers with high spending scores, and so on.

# Dataset
The dataset, Mall_Customers.csv, includes:

CustomerID: Unique identifier for each customer
Gender: Gender of the customer (categorical)
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousands of dollars
Spending Score (1-100): Spending score assigned based on customer behavior and spending patterns

# Selected Features
For this clustering analysis, we used:

Annual Income (k$): Annual income serves as an indicator of purchasing power.
Spending Score (1-100): Score assigned to gauge customer engagement and spending patterns.

# Clustering Approach
Data Standardization:

The features are standardized to ensure they are on a comparable scale, which improves clustering performance.
Elbow Method:

Used to determine the optimal number of clusters by plotting the sum of squared distances (inertia) and observing the "elbow" point.
K-means Clustering:

With the selected number of clusters (e.g., 5 clusters), we apply K-means to segment customers into groups.
Evaluation
The Elbow Method plot helps determine the optimal number of clusters by identifying the "elbow" point where adding more clusters yields diminishing returns in reducing inertia.

# Visualizations
The clustering results are visualized using a scatter plot:

Customer Segments Plot: Shows clusters based on Annual Income and Spending Score.
Cluster Centroids: Red markers indicate centroids for each cluster, helping us understand the central tendencies of each group.

# Results
The segmentation creates distinct customer groups, which can be interpreted as follows:

High-income, high-spending customers
Low-income, low-spending customers
High-income, low-spending customers, etc.
These groups enable targeted strategies, such as rewards programs for high-spending customers and engagement efforts for low-spending groups.
