# PRODIGY-02-ML
K-Means Clustering on Mall Customer Segmentation
This project demonstrates how to use the K-Means clustering algorithm to group customers of a retail store based on their purchasing behavior. The dataset contains information about 200 mall customers, including their gender, age, annual income, and spending score. The goal is to segment the customers into different groups that share similar patterns based on these features.

Project Workflow:
1. Data Loading and Exploration:
The dataset is loaded and explored using pandas.
Initial descriptive statistics and visualizations are created to understand the data distribution.
Missing values are handled, and unnecessary columns like CustomerID are dropped.

2. Data Preprocessing:
The Gender column is converted into numerical format (0 for Male, 1 for Female).
The features are scaled using StandardScaler for better clustering performance.

3. Elbow Method:
The Elbow method is used to determine the optimal number of clusters (K) for the K-Means algorithm.
A range of values for K is tested, and the within-cluster sum of squares (inertia) is plotted to identify the best value for K.

4. K-Means Clustering:
K-Means clustering is applied with the optimal number of clusters.
The clustering results are added to the original dataset for analysis.
The Silhouette Score is calculated to evaluate the quality of the clustering.

5. Visualization:
The clusters are visualized using scatter plots, showing the relationships between Annual Income and Spending Score for each cluster.
Additionally, Principal Component Analysis (PCA) is applied to reduce dimensionality, enabling a better visual understanding of the clusters.

Key Libraries Used:
pandas for data manipulation.
matplotlib for data visualization.
sklearn for scaling, clustering, and evaluation (K-Means, Silhouette Score, PCA).

Dataset:
The dataset used for this project is available on Kaggle: Mall Customers Dataset
