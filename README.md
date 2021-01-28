# CreditCard_CustomerSegmentation_Clustering
Agglomerative Hierarchical method, Density based DBScan and Distribution model-based Gaussian Mixture Models on credit card dataset

## Introduction
This notebook explores the use of clustering as data exploration for customer segmentation by analyzing usage behavior of about 9000 active credit card holders during a 6 month period. Typically there are models such as RFM model, LTV models, etc., to perform such task. Here the data is used as-is (with some scaling, etc.) to perform clustering.

The dataset taken from Kaggle as credit card dataset that can be found here. The goal is to segment the customers into groups, to reveal (any) hidden pattern within the customers with no knowledge of labels.
Three approaches implemented are Hierarchical method, Density based and Distribution model-based:

Hierarchical Clustering
DBScan
Gaussian Mixture Models
This dataset does not have label, hence it is an illustration of using unsupervised techniques. For each method, following approach is taken:

Perform clustering choosing between 3-5 clusters
Using the original unscaled data (without the customer ID), calculate the mean of each cluster
Analyse the results and findings
This is a very simple approach to customer segmentation assigning the customers into groups, and try to extract some common features from observations within the same group.

## Results
Results demonstrate that for the credit card dataset, Hierarchical Clustering is the best method out of the three for customer segmentation since the features are clustered better revealing more information than in others.
