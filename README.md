# Cryptocurrency Clustering Challenge

In this challenge, knowledge of Python and unsupervised learning are used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.


1. Prepare the Data: Use StandardScaler() to normalize the data.

**Original Data**
![](Pics/original_data.png)
![](Pics/original_data_chart.png)

**Scaled Data**
![](Pics/scaled_data.png)
![](Pics/scaled_data_chart.png)


2. Find the Best Value for k Using the Original Scaled DataFrame

![](Pics/elbow_chart.png)

- What is the best value for k?
**4**

3. Cluster Cryptocurrencies with K-means Using the Original Scaled Data

![](Pics/predictions_chart.png)

4. Optimize Clusters with Principal Component Analysis

![](Pics/variances.png)

-What is the total explained variance of the three principal components?
**89.50%**

**PCA DataFrame**
![](Pics/pca_df.png)

5. Find the Best Value for k Using the PCA Data

![](Pics/elbow_pca_chart.png)

-What is the best value for k when using the PCA data?
**4**

-Does it differ from the best k value found using the original data?
**No, the best value for `k` is the same**

6. Cluster Cryptocurrencies with K-means Using the PCA Data

![](Pics/predictions_pca_chart.png)

7. Visualize and Compare the Results





-What is the impact of using fewer features to cluster the data using K-Means?
