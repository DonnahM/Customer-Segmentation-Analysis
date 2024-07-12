# Customer Segmentation Analysis

## 1. Introduction
Customer segmentation is crucial for businesses to tailor their marketing efforts and improve customer satisfaction. This project aims to analyze customer data to identify distinct segments and develop targeted marketing strategies.

## 2. Business Understanding

### Problem Statement
Businesses often struggle to understand the diverse needs and behaviors of their customer base. A one-size-fits-all approach to marketing and customer engagement can lead to suboptimal results. By segmenting customers based on their demographic and behavioral data, businesses can tailor their marketing efforts to meet the specific needs of each segment, thereby enhancing customer satisfaction and boosting sales.

#### Main Objective
To analyze customer data to identify distinct segments within the customer base. This segmentation will help in developing targeted marketing strategies, improving customer satisfaction, and increasing sales.

##### Key Objectives
- Analyze the demographic and behavioral traits of each segment to understand their preferences and needs.
- Create customized marketing and engagement strategies for each segment to improve customer satisfaction and increase sales.
- Describe each segment based on key demographic and behavioral attributes.
- Provide recommendations for targeted marketing and customer engagement strategies.

## 3. Data Understanding
The dataset was extracted from Kaggle and includes 1000 rows and 9 columns of customer data.

## 4. Data Preparation
Data cleaning revealed no missing or duplicate values.
Feature engineering involved encoding categorical variables.

## 5. Exploratory Data Analysis (EDA)
Age: Most customers are aged between 30 and 60 years.
Income: Customer income is widely distributed, with many earning between 50,000 and 120,000 annually.
Spending Score: Spending scores are fairly evenly distributed, with a concentration around the 50-75 range.
Preferred Category: The Sports category is the most preferred, followed by Groceries and Electronics.
Gender: The dataset has a higher number of male customers.
## 6. Clustering Analysis
#### K-means Clustering
Applied K-means clustering with k=5 based on exploratory analysis.
Cluster profiles were analyzed to understand the characteristics of each segment.

#### DBSCAN Clustering
DBSCAN was attempted with parameter tuning. The best silhouette score obtained was 0.189, indicating moderate cluster quality.
Agglomerative Clustering and Gaussian Mixture Models
Agglomerative Clustering and Gaussian Mixture Models (GMM) were also considered, but results were less promising compared to K-means.

## 7. Cluster Profiles
##### Cluster 0
Age: Mainly younger customers.
Income: Moderate.
Spending Score: Low.
Recommendations: Focus on budget-friendly promotions and introductory offers.
##### Cluster 1
Age: Older customers.
Income: Moderate.
Spending Score: Moderate.
Recommendations: Emphasize quality and personalized service.
##### Cluster 2
Age: Middle-aged customers.
Income: High.
Spending Score: High.
Recommendations: Focus on premium offerings and personalized experiences.
#####  Cluster 3
Age: Older customers.
Income: Low.
Spending Score: Moderate.
Recommendations: Offer cost-effective solutions and discounts.
##### Cluster 4
Age: Mainly younger customers.
Income: Moderate.
Spending Score: High.
Recommendations: Leverage digital marketing channels and personalized recommendations.
## 8. Recommendations
Targeted Marketing Strategies
Develop budget-friendly promotions for Cluster 0.
Emphasize quality and personalized service for Cluster 1.
Offer premium products and loyalty programs for Cluster 2.
Provide cost-effective solutions for Cluster 3.
Use digital marketing to engage Cluster 4.
Customer Engagement
Implement tailored engagement strategies to maintain loyalty and increase sales.
## 9. Future Work
Further Refinement
Experiment with other clustering algorithms and parameter tuning to potentially improve clustering results.
Additional Data
Consider incorporating additional data sources (e.g., customer feedback, transaction history) for more comprehensive segmentation.
Limitations
Discuss any limitations of the current analysis, such as the moderate silhouette scores for certain clustering methods.
## 10. Final Note
The project demonstrates the importance of customer segmentation in developing effective marketing strategies. Despite moderate silhouette scores for DBSCAN, the K-means clustering provided actionable insights into customer segments.