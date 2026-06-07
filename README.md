# Customer Segmentation Using K-Means Clustering

## Overview

This project applies unsupervised machine learning techniques to segment customers based on purchasing behavior. Using K-Means Clustering, customers are grouped according to annual income and spending patterns, enabling data-driven business insights and targeted marketing strategies.

The project covers the complete analytics workflow including data cleaning, exploratory data analysis, feature visualization, cluster optimization, customer segmentation, and business interpretation.

---

## Dataset

The dataset contains customer demographic and behavioral information including:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

### Features Used for Clustering

- Annual Income
- Spending Score

---

## Methodology

### Data Preprocessing

- Removed unnecessary identifiers
- Renamed features for improved readability
- Checked for missing values and inconsistencies

### Exploratory Data Analysis

- Analyzed customer demographics
- Examined income and spending distributions
- Visualized relationships between customer attributes
- Performed correlation analysis

### Customer Segmentation

Implemented K-Means Clustering to group customers with similar purchasing behavior.

### Optimal Cluster Selection

Used the Elbow Method (WCSS) to determine the optimal number of clusters.

### Cluster Analysis

Generated customer segments and interpreted behavioral patterns for each cluster.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Key Learning Outcomes

- Exploratory Data Analysis (EDA)
- Data Visualization
- Customer Behavior Analytics
- Unsupervised Learning
- K-Means Clustering
- Business Intelligence & Segmentation

---

## Results

- Identified five distinct customer segments.
- Distinguished high-value, balanced, and low-engagement customer groups.
- Demonstrated how clustering techniques can support targeted marketing and business decision-making.

---

## Business Insights

### Cluster 1 – High Value Customers
High income and high spending behavior. Represents premium customers with strong revenue potential.

### Cluster 2 – Cautious Customers
High income but relatively low spending. Potential target for personalized marketing campaigns.

### Cluster 3 – Balanced Customers
Moderate income and moderate spending behavior.

### Cluster 4 – Budget Customers
Lower income and lower spending activity.

### Cluster 5 – High Engagement Customers
Lower income but high spending behavior, indicating strong purchasing engagement despite budget constraints.

---

## Conclusion

Successfully segmented customers into meaningful groups using K-Means Clustering. The analysis highlights how unsupervised learning can uncover hidden behavioral patterns and support strategic business recommendations.

---

## Repository Structure

```text
Customer-Segmentation-KMeans/

├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
└── README.md
```
