# CryptoClustering
This challenge focuses on Python and unsupervised learning to predict if cryptocurrencues are affected by 24-hr or 7-day prive changes.

## Prepare the Data
- Use the *StandardScaler()* module from scikit-learn to normalize the data from the CSV file.
## Find the Best Value for k Using the Original Scaled DataFrame
Use the elbow method to find the best value for k using the follwoing steps:
- Create a list with the number of k values from 1 to 11.
- Create an empty list to store the inertia values.
- Create a for loop to compute the inertia with each possible value of k.
- Create a dictionary with the data to plot the elbow curve.
- Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
- Answer the following question in your notebook: What is the best value for k?
  
## Cluster Cryptocurrencies with K-means Using the Original Scaled Data
Use the following steps to cluster the cryptocurrencies for the best value for k on the original scaled data:
- Initialize the K-means model with the best value for k.
- Fit the K-means model using the original scaled DataFrame.
- Predict the clusters to group the cryptocurrencies using the original scaled DataFrame.
- Create a copy of the original data and add a new column with the predicted clusters.
- Create a scatter plot using hvPlot as follows:
      - Set the x-axis as "PC1" and the y-axis as "PC2".
      - Color the graph points with the labels found using K-means.
      - Add the "coin_id" column in the hover_cols parameter to identify the cryptocurrency       represented by each data point.

## Optimize Clusters with Principal Component Analysis

## Find the  Best Value for k Using the PCA Data

## Cluster Cryptocurrencies with K-means using the PCA data
   *What is the impact of using fewer features to cluster the data using K-Means?*
