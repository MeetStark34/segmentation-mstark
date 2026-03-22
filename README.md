# Smart Customer Behavior Analysis System

## Project Overview
This project analyzes customer transactions to segment users based on RFM analysis and K-Means clustering.

## Features
- RFM (Recency, Frequency, Monetary) analysis
- Customer segmentation using K-Means
- Data visualization
- Business insights

## Tech Stack
Python, Pandas, (K-means) Scikit-learn, Matplotlib, Seaborn

## Output
- Customer clusters
- Behavioral insights
- Visual analysis

## Customer Segmentation Insights (Final Clusters)

The clustering analysis identified three distinct customer segments based on RFM (Recency, Frequency, Monetary) metrics:

- **Cluster 2** represents high-value customers, characterized by low recency (23 days), very high purchase frequency (~38 transactions), and the highest monetary contribution (~703). These customers are highly engaged and contribute significantly to overall revenue.

- **Cluster 1** consists of moderate-value customers, with moderate recency (~47 days), moderate purchase frequency (~7.6), and moderate spending (~113). These customers are relatively active but have the potential to increase their engagement and value.

- **Cluster 0** represents low-value or churn-risk customers, characterized by very high recency (~248 days), low purchase frequency (~3.2), and low spending (~54). These customers are largely inactive and at risk of being lost.

Overall, the segmentation clearly differentiates between high-value, mid-tier, and low-engagement customers. These insights enable businesses to implement targeted strategies such as retention programs for high-value customers, upselling for moderate customers, and reactivation campaigns for churn-risk customers.
