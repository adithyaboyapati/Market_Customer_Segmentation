
# Market Segmentation in Insurance



## Objective
This case requires to develop a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups.
<img align="center" src="https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png" alt="image">

## Data Description

The dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

## Data:

Use the below link to download the Data Set:

URL : https://www.kaggle.com/arjunbhasin2013/ccdata

## Approach:
* Data Description
  * We will be using the Credit Card segmentation data set present in the Kaggle Repository. This Data set is satisfying our data requirement. 

* Data Preprocessing
  * After the initial analysis We found that there are 313 missing values in MINIMUM_PAYMENTS and 1 missing value in CREDIT_LIMIT. We have replaced the missing values with mean.
  
* Model Training
  * We trained various models in our notebook and K-Means was a good fit.

* Model Evaluation
  * We have used silhoutte score to decide the number of clusters

* Model Saving
  * we will save our model so that we can use them for prediction purpose.

* Push to app
  * Here we also create our Streamlit app and user interface and integrate our model with Streamlit and UI

* Data from client side for prediction purpose
  * Now our application on cloud is ready for doing prediction. The prediction data which we receive from client side based on the data given the model will recommend the cluster a particular user belonging to.

 Web Deployment
 ===================================
Market Segmentation Web App : https://marketsegmentation01.herokuapp.com/

Screenshots
====================================
**Homepage interface:**

![image](https://user-images.githubusercontent.com/24864663/156436706-d42fbb3b-c124-44e4-a93c-a44be06c96b3.PNG)
![image](https://user-images.githubusercontent.com/24864663/156436752-dbfd50f8-8c1c-47f0-a274-85c98f817c5f.PNG)
![image](https://user-images.githubusercontent.com/24864663/156436759-f1b69608-47cb-4c3e-80ef-57c6aaf5b1f5.PNG)

**Prediction:**

![PRED-1](https://user-images.githubusercontent.com/24864663/156437402-234f57f7-2862-476c-a395-bb22b53c5976.PNG)
![PRED-2](https://user-images.githubusercontent.com/24864663/156437414-6bd4c8d8-cdea-4dad-b054-13357fffed4a.PNG)

## Summary for the Prediction

Output will be the Cluster number along with the characteristic of the cluster feature that it belongs to  

## Algorithms used :
In this dataset I have used three clustering algorithm to perform segmentation.These algorithms are given below.
- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)


