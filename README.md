
# Customer Segmentation using K-Means Clustering

This repository provides a Python implementation of K-Means clustering for segmenting retail store customers based on their purchase behavior. The algorithm groups customers into clusters using features such as Annual Income and Spending Score, enabling data-driven decision-making for marketing strategies.

# Features

**Interactive Analysis:**  Users can select the number of clusters dynamically using the Elbow Method.

**Visualization:**  Provides 2D plots of clusters and centroids for better understanding of customer segments.

**Scalable:** Can handle datasets with multiple numerical features.

# Dataset

The dataset used for this implementation is the Mall_Customers.csv file, which contains the following attributes:

**CustomerID:** Unique identifier for each customer.

**Gender:**  Gender of the customer.

**Age:**  Age of the customer.

**Annual Income (k$):**  Annual income in thousands of dollars.

**Spending Score (1-100):**  A score assigned based on spending behavior and purchasing patterns.




Specify the features to use for clustering.

Define the number of clusters.

View the generated visualizations and clustered data.

# Results

The script produces:

**Clustered Data:** The dataset with an additional column indicating the cluster each customer belongs to.

**Cluster Visualization:** A scatter plot showing clusters and their centroids (for 2D features).

**Exported Data:** Clustered data is saved as a CSV file (Clustered_Customers.csv).

# Acknowledgments

The dataset is publicly available and used for educational purposes.

Built using the scikit-learn and matplotlib libraries.

