# Customer Segmentation Analysis

## Oasis Infobyte Data Analytics Internship

**Level:** 1  
**Task:** 2 – Customer Segmentation Analysis  
**Project By:** Pornima Onkar Nerkar

---

## 1. Project Overview

This project focuses on segmenting e-commerce customers based on their purchasing behaviour using RFM (Recency, Frequency, Monetary) analysis and the K-Means clustering algorithm.

The goal is to identify different customer groups and provide targeted marketing recommendations to improve customer engagement and retention.

## 2. Objectives

- Analyse customer purchasing behaviour.
- Calculate Recency, Frequency, and Monetary values.
- Apply K-Means clustering to identify customer segments.
- Visualise and profile the customer groups.
- Provide business insights and marketing recommendations.

## 3. Dataset

- **Dataset Name:** Online Retail Dataset
- **Source:** UCI Machine Learning Repository
- **Link:** https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains 541,909 transaction records from a UK-based online retailer.

### Dataset Columns

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## 4. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 5. Project Workflow

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. RFM feature engineering
5. Feature scaling using StandardScaler
6. K-Means clustering
7. Cluster visualisation and profiling
8. Business insights and recommendations

## 6. Customer Segmentation Results

Four customer segments were identified using K-Means clustering.

| Cluster | Recency | Frequency | Monetary |
|---|---:|---:|---:|
| 0 | 18.12 | 2.15 | 551.82 |
| 1 | 12.13 | 13.71 | 8074.27 |
| 2 | 71.08 | 4.08 | 1802.83 |
| 3 | 182.50 | 1.32 | 343.45 |

## 7. Business Insights and Recommendations

### Cluster 0 – Recent, Occasional Customers
These customers purchased recently but have relatively low purchase frequency and spending.

**Recommendation:** Use welcome-back offers, product recommendations, and personalised promotions to encourage repeat purchases.

### Cluster 1 – Loyal, High-Value Customers
These customers purchase frequently and have the highest average monetary value.

**Recommendation:** Provide loyalty rewards, exclusive discounts, VIP benefits, and early access to new products.

### Cluster 2 – Moderately Active Customers
These customers show moderate purchase frequency and spending but have not purchased as recently as the first two segments.

**Recommendation:** Use personalised product suggestions, limited-time offers, and targeted campaigns to increase engagement.

### Cluster 3 – At-Risk or Inactive Customers
These customers have the highest average recency and relatively low purchase frequency and spending.

**Recommendation:** Run re-engagement campaigns, send special discount coupons, and provide incentives to encourage another purchase.

## 8. Conclusion

RFM analysis and K-Means clustering helped identify four distinct customer segments. The results can help businesses understand customer purchasing behaviour and develop targeted marketing strategies to improve customer engagement, retention, and sales.

## 9. Project Files

- `PornimaNerkar_Task2_Customer_Segmentation.ipynb` – Jupyter Notebook containing the analysis and visualisations.
- `Online Retail.xlsx` – Dataset used for the analysis.
- `README.md` – Project documentation.

## 10. Author

**Pornima Onkar Nerkar**  
Oasis Infobyte Data Analytics Intern
