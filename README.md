**Preliminary Note
------------------
The thesis is complete and submitted in April, 201. It will be made public here once the marking process is done**

## Bachelor Thesis
# Application of Data Mining Methods for Customer Clustering
============================================================

## Abstract
-----------
Knowing its customers is essential for a company’s success. Esp. in the age of e-commerce, where customers became just rows of lists, it is important to target them more individually. The traces buyers leave in an online-store, allow detailed insights on their habits how they interact with an organization. Their purchase history contains all transactional data to build meaningful customer segments. These segments allow more targeted communication and actions towards customers.

The motivation behind this thesis is to investigate the value of clustering in the machine learning/data mining context for customer segmentation. Classical database marketing methods are combined with data mining tools. Data mining techniques can be used to create the segments automatically. The outcome shows that machine learning can be applied successfully for the needs of small and medium organizations and can help in handling a growing customer base.

## Contents
-----------
1. Introduction
    1. Commoditization of E-Commerce
    2. Targeting customers
    3. The road-map of this thesis
2. Customer segmentation
    1. Overview
    2. Cohort Analysis
    3. RFM Analysis
        1. The Metrics
        2. Working with the segmented data
        3. Critical Appraisal
        4. Chapter summary and outlook
3. Data Collection
4. Pre-processing
   1. Preparation
   2. Featurescalingg
   3. Standardizing
5. Clustering
   1. Applying clustering for segmentation
   2. Interpreting the cohort analysis
   3. Selecting algorithms for comparative analysis
   4. Choosing the number of clusters
   5. ApplyingClusteringAlgorithms
       1. K-Means
       2. Agglomerative
       3. DBSCAN
6. Evaluation
    1. Cohort Analysis
    2. Clustering using the RFM approach
        1. Quality ofs segmentation
        2. Cluster sizes
        3. Cluster boundaries
        4. Numberofclusters
7. Conclusions

## Exemplary data visualisations and outcomes (based on Shopify Store Data)
The underlying data for the analysis was collected from a Shopify store with about 5.000 customers, 12.000 orders, and a total of 30.000 sold items.

### K-Means applied on aggregated customer data with the dimensions Recency, Frequency and Monetary Value
![alt text](https://github.com/zinyosrim/customer-clustering-thesis/raw/master/Kmeans_transformed.png "Aggregated customer data of a Shopify store was clustered using the K-Means algorithm")

### The Cohort Analysis applied to Shopify data shows to which extent a store is doing well with regard to customer retention 
![alt text](https://github.com/zinyosrim/customer-clustering-thesis/raw/master/Cohort_analysis.png "Cohort Analysis applied on aggregated customer data of a Shopify store")

*Stay tuned, more to come...*
