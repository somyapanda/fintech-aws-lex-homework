# unit13-challenge

## Clustering Crypto

This repository contains the Jupyter notebooks, accompanied with the machine learning libraries such as sklearn and AWS services as part of the Fintech homework assignment Unit 13 Homework Assignment - The Power of the Cloud and Unsupervised Learning.

In this homework, we have created a report about cryptocurrencies that are available on the trading market. This report is intended to help the investment bank to understand about the properties and behavior of these coins, so it can create a better cryptocurrencies investment portfolio for its customers.


## Files

### [Crypto Clustering](crypto_clustering.ipynb)

In this section, 

- load the information about cryptocurrencies by using read_csv funtion.

- perform data preprocessing tasks:

        - remove unnecessary columns
        
        - remove null values
        
        - create a dataframe with all the tradable cryptocurrencies
        
        - create a dataframe of dummy variables for all the text features
        
        - use `StandardScaler` from `sklearn` library for standardizing the data

- use `PCA` and `KMeans` algorithms from `sklearn` machine learning library for dimension reduction and clusters prediction.

       - create a dataframe with the reduced data dimensions
       
       - create an elbow curve to find the best k value
       
       - use k value to predict the `k` clusters for the cryptocurrencies 

- plot 3D scatter using `Plotly Express` to show additional infomation on each data point.

- create a table with all the current tradable coins by using `hvplot.table`.

- create scatter plot to contrast the number of available coins versus the total number of mined coins.


### [Crypto Clustering SageMaker](crypto_clustering_sm.ipynb)

In this section,

- use the `altair` library

         - create elbow curve
         
         - visualize the clusters through scatter plot
         
         - create a table of tradable coins by using `display` function


