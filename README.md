# Cryptocurrencies

## Overview:
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. The goal is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. The data to be worked with is not ideal, so it will need to be processed to fit the machine learning models. The way to go about this is unsupervised learning. To group the cryptocurrencies, a clustering algorithm will be used. Then, data visualizations will be used to share findings.

## Deliverables:
* Deliverable 1: Preprocessing the Data for PCA
* Deliverable 2: Reducing Data Dimensions Using PCA
* Deliverable 3: Clustering Cryptocurrencies Using K-means
* Deliverable 4: Visualizing Cryptocurrencies Results

## Results:
After the preprocessing and cleaning phase there are 532 tradable cryptocurrencies.

## Clustering Cryptocurrencies using K-Means - Elbow Curve:

![bokeh_plot](https://user-images.githubusercontent.com/85847344/138414857-d0a86451-5694-47be-8233-d4291adb1a98.png)

* The best k value appears to be 4 so it is clear that an output of 4 clusters to categorize the crytocurrencies should be chosen. 

## 3D-Scatter plot with clusters

<img width="484" alt="Screen Shot 2021-10-22 at 1 04 24 AM" src="https://user-images.githubusercontent.com/85847344/138417231-edbe2bb9-2f10-4342-a73f-8e7910573862.png">

* A 3D-Scatter plot was created with the PCA data and the clusters

## 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply

![bokeh_plot copy](https://user-images.githubusercontent.com/85847344/138415542-b1441d3a-3b9f-4546-b77a-f3552e20612e.png)

*  The PCA algorithm is the right method for better visualizations, not this 2D-Scatter plot because it does not efficiently segregate the different classes in the same way the PCA does.

## Tradable Cryptocurrencies Table

<img width="689" alt="Screen Shot 2021-10-22 at 12 54 26 AM" src="https://user-images.githubusercontent.com/85847344/138415693-e6da4bf3-4151-42bf-a7e4-0593af5bc223.png">

* Most of the cryptocurrencies are part of class #0 and #1

## Summary
Through analysis there are 532 identified cryptocurrencies based on similarities of their features. In order to determine the potential interest and performance of each group for the investment bank's clients, each of their particualrities need to be analyzed.
