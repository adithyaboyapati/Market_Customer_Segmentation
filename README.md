
# Market Segmentation in Insurance



## Objective
This case requires to develop a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups.
<img align="center" src="https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png" alt="image">

## Data Description

The dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

## Data:

Use the below link to download the Data Set:

URL : https://www.kaggle.com/arjunbhasin2013/ccdata

## Algorithms used :
In this dataset I have used three clustering algorithm to perform segmentation.These algorithms are given below.
- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)

## Final Model :

We have created a Streamlit Application based on this clustering technique, where we are taking the customer details & identifying which cluster the custoemr belongs to.
