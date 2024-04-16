# Clustering for Targeted Marketing Strategy using Credit Card Data
## About
This case explores customer segmentation on credit card users using machine learning clustering algorithms to develop targeted marketing strategies

Data Source: [AnalytixLabs](www.analytixlabs.co.in), [Kaggle](https://www.kaggle.com/kashyaprahul/credit-card-segmentation)

Refer to the [Case Study Document](https://github.com/tonyshumlh/credit_card_cluster_open/blob/master/data/datasets_49737_90340_CREDIT%20CARD%20-%20SEGMENTATION%20CASE%20STUDY.pdf) for more details of the open dataset

---
## Abstracts
This case  explores customer segmentation on credit card users using machine learning clustering algorithms to develop targeted marketing strategies, with a sample dataset of the usage behaviour of 9000 credit card holders from Kaggle during the last 6 months.

Data wrangling and feature engineering are performed specifically for finance context. Data preprocessing with standardisation and principal component analysis are then performed. User clustering is made with the provided data using K-means and DBSCAN technique with hyper-parameter tuning.

Upon evaluation of clusters from both techniques, 7 distinct clusters from K-Means are chosen. On the other hand, DBSCAN results in 1 large cluster with most users due to the heavily skewed features distributions in the dataset, and it is less preferred.

After interpreting the cluster characteristics, three main customer groups are identified and targeted marketing strategies are recommended as follows.
- Good Customers (Cluster 1, 3, 5): big spenders with ~ 1100 customers. The strategy is to retain them and maintain their high level of spending.
- Customers with Potentials (Cluster 0, 2): mild spenders with ~ 4000 customers. The strategy is to incentivise them with more rewards or additional services for higher spending level.
- Non-performing Customers (Cluster 4, 6): small spenders with ~ 3700 customers. The strategy is to retain them with low cost. Further study on their demands is needed for designing the better strategy.

Some possible next steps, including evaluating marketing campaign effectiveness, iterating on clustering techniques, are recommended. Studying new users is also suggested for gaining insights of them for prompt marketing strategies.

---
## Contents

### 1. Data Preparation
- Basic Data Exploration
- Null Value Handling

### 2. Data Exploration
- Feature Enrichment
- Variables Exploration

### 3. Feature Engineering
- Standardization
- Principal Component Analysis

### 4. Customers Clustering
- Method 1: K-means
- Method 2: DBSCAN

### 5. Cluster Characteristics and Marketing Strategy
- Cluster Characteristics
- Marketing Strategy

### 6. The Next Steps