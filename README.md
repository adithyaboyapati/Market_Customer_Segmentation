
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

![image](https://user-images.githubusercontent.com/92853376/152312227-bf8d75e1-5169-4669-af01-a46c3a58fcf7.png)

**Prediction:**

![image](https://user-images.githubusercontent.com/92853376/152312323-0e664ff4-e5ab-48f1-a94d-f190ae6d9ad8.png)


## Algorithms used :
In this dataset I have used three clustering algorithm to perform segmentation.These algorithms are given below.
- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)


