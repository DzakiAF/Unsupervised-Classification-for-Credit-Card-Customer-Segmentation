# Customer Segmentation using K-Means

## 📌 Project Overview
This project performs **customer segmentation** for a bank using **K-Means clustering** based on credit card usage patterns over the past six months. The goal is to identify distinct customer groups to help the marketing team improve their strategies and provide personalized financial services.

## 📂 Dataset
- **Description**: The dataset contains various features related to credit card usage.
- **Main Features**:
  - `BALANCE`: Total balance on the credit card.
  - `BALANCE_FREQUENCY`: Frequency of balance updates.
  - `PURCHASES`: Total purchases made by the customer.
  - `ONEOFF_PURCHASES`: Total one-time purchases.
  - `INSTALLMENTS_PURCHASES`: Total installment purchases.
  - `CASH_ADVANCE`: Total cash advance taken.
  - `PURCHASES_FREQUENCY`: Frequency of purchases.
  - `ONEOFF_PURCHASES_FREQUENCY`: Frequency of one-time purchases.
  - `PURCHASES_INSTALLMENTS_FREQUENCY`: Frequency of installment purchases.
  - `CASH_ADVANCE_FREQUENCY`: Frequency of cash advances.
  - `CASH_ADVANCE_TRX`: Number of cash advance transactions.
  - `PURCHASES_TRX`: Number of purchase transactions.
  - `CREDIT_LIMIT`: Credit limit of the customer.
  - `PAYMENTS`: Total payments made by the customer.
  - `MINIMUM_PAYMENTS`: Minimum payments made.
  - `PRC_FULL_PAYMENT`: Percentage of full payments made.
  - `TENURE`: Number of months the customer has been with the bank.

## 🔧 Tech Stack
- **Python**
- **Pandas & NumPy** (Data Processing)
- **Scikit-learn** (Clustering)
- **Matplotlib & Seaborn** (Visualization)

## 📌 Workflow
1. **Exploratory Data Analysis (EDA)**
   - Identifying missing values and handling them
   - Understanding distribution and correlations
   - Visualizing spending patterns
2. **Feature Scaling & Preprocessing**
   - Standardizing numerical features for better clustering performance
3. **Clustering with K-Means**
   - Finding the optimal number of clusters using **Elbow Method** and **Silhouette Score**
   - Applying **K-Means clustering** to segment customers
4. **Cluster Analysis & Business Recommendations**
   - Analyzing each cluster’s characteristics
   - Providing insights for marketing strategies

## 📊 Results
- **Optimal Clusters**: 4
- **Clustering Insights**:
  - Different customer groups based on spending habits, transaction frequency, and credit usage
  - Business recommendations for targeted marketing strategies

## 🤝 Contribution
If you would like to contribute, please **fork** this repository and submit a **pull request** with your proposed changes!

---
✨ **Created by DzakiAF**

