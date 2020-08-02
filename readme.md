# Credit Card Data for Clustering
This case is to develop a customer segmentation on credit card users to define marketing strategy.

Data Source: [AnalytixLabs](www.analytixlabs.co.in), [Kaggle](https://www.kaggle.com/kashyaprahul/credit-card-segmentation)

Refer to the [Case Study Document](https://github.com/tonyshumlh/credit_card_cluster_open/blob/master/datasets_49737_90340_CREDIT%20CARD%20-%20SEGMENTATION%20CASE%20STUDY.pdf) for more details of the open dataset

## Contents

#### 0. Abstracts
#### 1. Data Preparation
- Basic Data Exploration
- Null Value Handling

#### 2. Data Exploration
- Feature Enrichment
- Variables Exploration

#### 3. Feature Engineering
- Standardization
- Principal Component Analysis

#### 4. Customers Clustering
- Method 1: K-means
- Method 2: DBSCAN

#### 5. Cluster Characteristics and Marketing Strategy
- Cluster Characteristics
- Marketing Strategy

#### 6. The Next Steps

---
### 0. Abstracts
This case is to develop a customer segmentation on credit card users to define marketing strategy. The sample dataset summarizes the usage behaviour of about 9000 active credit card holders during the last 6 months.

In the 1st part, we explored the data, performed data cleansing and enriched the datasets with more metrics. Then we did feature engineering with standardization and principal component analysis, and clustered the users based on both K-means and DBSCAN methods.

After evaluating the 2 methods, we chose the 7 clusters based on K-means as many features in our dataset are heavily skewed, and it leads to 1 big cluster with most users using DBSCAN. K-means is more preferred.

After that, we studied the clusters characteristics, categorized into 3 bigger groups and suggested on marketing strategies per cluster.
- Good Customers (Cluster 0, 2, 4) who are the big spenders and consist of ~ 1100 customers. Our strategy is to retain them and maintain their high level of spending.
- Customers with Potentials (Cluster 1, 5) who are mild spenders and consist of ~ 4000 customers. Our strategy is to incentify them for higher spending with more rewards or additional services.
- Non-performing Customers (Cluster 3, 6) who are small spenders and consist of ~ 3700 customers. Our strategy is to retain them with low cost and study their demands to design the strategy in the future.

The next steps will be to evaluate the effectiveness of marketing campaigns after implemented, and iteratively make improvements on the campaigns and clustering. Moreover, we can work on acquisition of new users and engagement of first time users by studying the correlation between their attributes and behaviours and making classification.
