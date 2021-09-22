# Cryptocurrencies - Berkeley DA
Yae Jin Park\
Module 18 - Unupervised Machine Learning and Cryptocurrencies

## Overview
Not all datasets in the real world come with classification labels and this is when unsupervised learning becomes useful to analyze said datasets. In this challenge, my main objective is to analyze unlabeled cryptocurrency data with a couple of unsupervised learning techniques. The following steps were taken in order to analyze the data:
* Data was scaled with standard scaler.
* Then, the data was processed with PCA to reduce the dimensions to three components and to predict which class each cryptocurrency belongs to.
* The processed data were clustered via K-means clustering with each cluster representing the class prediction of each cryptocurrency predicted.
* Plots were generated for visualization of the results.

Please refer to the Jupyter Notebook file titled 'crypto_clustering.ipynb' in the 'challenges' folder.

## Results
Please refer to this section if, for some reason, you have problems with loading the output plots in the Jupyter file.

![3d](https://github.com/yaejinpark/cryptocurrencies/blob/main/resources/images/scatter_plot_3d.png)
![2d](https://github.com/yaejinpark/cryptocurrencies/blob/main/resources/images/scatter_plot_2d.png)