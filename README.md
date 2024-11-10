# credit_score_customer_segmentation
This project focuses on segmenting customers based on their credit scores derived from multiple financial factors.

# Project Objective
The primary goal is to categorize customers into distinct groups that reflect their qualification for a loan or credit card with lower interest rates and/or better payment terms. This helps financial institutions to make informed decisions on loans and credit risks.

# Project Overview
The process involvves applying data preprocessing and analysis techniques to clean, transform, and explore the data. After calculating a composite credit score based on weighted factors, K-means clustering was used to segment customers into categories that reflect standard FICO credit score ranges. 

# Technologies Used
- Python Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn
- Clustering Method: KMeans from Scikit-learn
- Data Visualization: Seaborn, Matplotlib

# Method Used
- Data Cleaning
- Data Preprocessing
- Data Visualization
- Exploratory Data Analysis
- Feature Scaling
- Credit Score Calculation
- Clustering (Customer Segmentation)

# Key Findings
- The Elbow Method suggested an optimal number of five clusters for customer segmentation.
- Each cluster corresponded to a FICO score range: Poor, Fair, Good, Very Good, and Excellent, which allowed for meaningful categorization based on credit scores.

# Conclusion
By segmenting customers based on credit score categories, this project provides a basis for targeted financial interventions. Customers in different clusters, from "Poor" to "Excellent," can be approached with tailored financial products, risk assessments, or support strategies. The segmentation enhances customer understanding and allows for data-driven decision-making in financial services.
