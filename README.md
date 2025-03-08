# E-commerce-Customers-Segmentation
Project Overview
This project aims to develop and train an unsupervised machine learning
model to segment customers based on their transactional behavior and other relevant features
from the dataset. The goal is to identify customer groups that share similar behaviors and use
these segments to discuss strategies for offering coupons to increase loyalty and satisfaction.

Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:

Data loading and inspection.
Handling missing values.
Data cleaning and formatting.
Exploratory Data Analysis
EDA involved exploring the data to answer key questions, such as:
1. Q&A
What is the optimal number of clusters for customer segmentation? Based on the Silhouette score, the optimal number of clusters (k) is 4.

How can we characterize each customer segment? The analysis reveals two distinct segments based on spending and coupon usage: Cluster 0 has lower spending and coupon usage, while Cluster 1 shows higher spending and coupon usage. More detailed analysis is necessary using the complete data and the optimal k = 4 to better characterize each segment.

2. Data Analysis Key Findings
Optimal Number of Clusters: The optimal k value, determined by maximizing the Silhouette score, is 4. The Silhouette score for k=4 was 0.2189714484284974, and its inertia was 9.713248867074801.
Cluster Characteristics (based on limited analysis with k=2): Two distinct clusters were identified using dummy data and k=2. Cluster 0 had lower average spending, average transaction value, and coupon usage frequency compared to Cluster 1.
Data Limitations: The initial analysis was hampered by the unavailability of transaction and coupon usage data, necessitating the use of dummy data for parts of the analysis, including the clustering evaluation with k = 2 and cluster characterization.
3. Insights or Next Steps
Complete Data Analysis: Re-run the analysis using the full dataset with the identified optimal k value of 4. Analyze the characteristics of each cluster (k=4) in detail using the complete "transactions.csv" and "coupon_usage.csv" files to gain meaningful insights for each of the 4 customer segments.
Coupon Strategy Development: Based on the complete cluster analysis, formulate targeted coupon strategies for each customer segment to maximize loyalty and satisfaction. For example, high-value customers may respond better to exclusive discounts, while low-value customers might be more sensitive to discounts on frequently purchased items.
