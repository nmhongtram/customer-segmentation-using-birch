# BIRCH in Customer Segmentation

## Project Overview
This project is the final assignment for the Introduction to Machine Learning course. The goal is to apply machine learning techniques to analyze and model the dataset obtained from Kaggle.

## Dataset
[Customer Dataset](https://www.kaggle.com/datasets/arezalo/customer-dataset/data)

## Machine Learning Techniques Used
- Data Preprocessing
- Feature Engineering
- Model Training & Evaluation
- Hyperparameter Tuning
- Visualization & Interpretation

## Results
The project applied the **BIRCH clustering algorithm** to segment customers based on their credit card usage behaviors. Key findings include:

- **Clustering Performance:**
  - BIRCH successfully grouped customers into meaningful segments using hierarchical clustering.
  - The **Silhouette Score**, **Calinski-Harabasz Index**, and **Davies-Bouldin Index** were used to evaluate cluster quality.
  - The BIRCH clustering approach was compared to **Agglomerative Hierarchical Clustering (HAC)**, showing that BIRCH performed efficiently with large datasets.

- **Customer Segmentation Insights:**
  - Customers were segmented based on spending patterns, frequency of purchases, and credit utilization.
  - The analysis revealed distinct customer groups, helping to identify high-value customers, low-spending customers, and those with irregular spending habits.

- **Model Comparison:**
  - BIRCH demonstrated advantages in handling large datasets efficiently while maintaining clustering accuracy.
  - HAC provided better-defined clusters but required more computational resources.
  - The results indicated that **BIRCH is suitable for large-scale customer segmentation applications**.

These insights can be applied in marketing strategies to personalize promotions, improve customer retention, and optimize financial services.

## Contributors
- Team 09
