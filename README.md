# CreditCard_CustomerSegmentation_Clustering
Approach uses Agglomerative Hierarchical method, Density based DBScan and Distribution model-based Gaussian Mixture Models on credit card dataset

## Introduction and Goal
This notebook explores the use of clustering as data exploration and analysis for customer segmentation by analyzing usage behavior of about 9000 active credit card holders during a 6 month period.  The goal is to segment the customers into groups, to reveal (any) hidden pattern within the customers with no knowledge of labels.

## Technique
Typically there are models such as RFM model, LTV models, etc., to perform such task. Here the data is used as-is (with scaling, etc.) to perform clustering.
The dataset taken from Kaggle as credit card dataset.
Three approaches implemented are Hierarchical method, Density based and Distribution model-based:

1. Hierarchical Clustering
2. DBScan
3. Gaussian Mixture Models
This dataset does not have label, hence it is an illustration of using unsupervised techniques. For each method, following approach is taken:

## Approach
1. Perform clustering choosing between 3-5 clusters
2. Using the original unscaled data (without the customer ID), calculate the mean of each cluster
3. Analyse the results and findings

## Analysis and Result
This is a simple approach to customer segmentation assigning the customers into groups, extracting some common features from observations within the same group.
Analysis of results demonstrate that for the credit card dataset, Hierarchical Clustering is the best method out of the three for customer segmentation since the features are clustered better revealing more information than in others.
