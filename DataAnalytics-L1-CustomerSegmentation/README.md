Customer Segmentation Analysis

Oasis Infobyte Data Analytics Internship

**Level:** 1  
**Task:** 2 – Customer Segmentation Analysis  
**Project By:** Pornima Onkar Nerkar

---

1. Project Overview

This project focuses on segmenting e-commerce customers based on their purchasing behaviour using RFM (Recency, Frequency, Monetary) analysis and the K-Means clustering algorithm.

The goal is to identify different customer groups and provide targeted marketing recommendations to improve customer engagement and retention.

2. Objective

- Analyse customer purchasing behaviour.
- Calculate Recency, Frequency, and Monetary values.
- Apply K-Means clustering to identify customer segments.
- Visualise and profile the customer groups.
- Provide business insights and marketing recommendations.

3. Dataset

**Dataset Name:** Online Retail Dataset  
**Source:** UCI Machine Learning Repository  
**Link:** https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains 541,909 transaction records from a UK-based online retailer.

Dataset Features

- InvoiceNo – Invoice number
- StockCode – Product code
- Description – Product description
- Quantity – Quantity purchased
- InvoiceDate – Transaction date and time
- UnitPrice – Price per unit
- CustomerID – Customer identification number
- Country – Customer's country

4. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

5. Project Workflow

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. RFM feature engineering
5. Feature scaling using StandardScaler
6. Optimal cluster selection using the Elbow Method
7. K-Means clustering with four clusters
8. Cluster visualisation and profiling
9. Business insights and recommendations

6. Data Cleaning

- Removed records with missing CustomerID values.
- Removed cancelled invoices.
- Removed transactions with non-positive quantities or prices.
- Calculated TotalAmount using Quantity × UnitPrice.

The cleaned dataset contained 397,884 transaction records.

7. RFM Analysis

Three customer behaviour features were calculated:

- **Recency:** Number of days since the customer's most recent purchase.
- **Frequency:** Number of distinct invoices per customer.
- **Monetary:** Total amount spent by each customer.

The analysis identified 4,338 unique customers.

8. Customer Segmentation Results

The Elbow Method was used to select four clusters.

| Cluster | Number of Customers | Customer Segment |
|---|---:|---|
| 0 | 837 | Recent, Occasional Customers |
| 1 | 716 | Loyal, High-Value Customers |
| 2 | 1,173 | Moderately Active Customers |
| 3 | 1,612 | At-Risk or Inactive Customers |

9. Business Insights and Recommendations

- **Cluster 0:** Encourage repeat purchases through personalised promotions and product recommendations.
- **Cluster 1:** Reward loyal, high-value customers with VIP benefits, exclusive discounts, and loyalty rewards.
- **Cluster 2:** Increase engagement through targeted campaigns and limited-time offers.
- **Cluster 3:** Run re-engagement campaigns and offer incentives to encourage customers to return.

10. Conclusion

The project successfully segmented e-commerce customers into four groups using RFM analysis and K-Means clustering.

The results provide useful insights into customer purchasing behaviour and can help businesses develop targeted marketing strategies, improve customer retention, and make data-driven decisions.

11. Project Files

- `PornimaNerkar_Task2_Customer_Segmentation.ipynb` – Jupyter Notebook containing the complete analysis and visualisations.
- `Online Retail.xlsx` – Original dataset used for the analysis.
- `README.md` – Project documentation.

---

**Intern:** Pornima Onkar Nerkar  
**Organisation:** Oasis Infobyte  
**Track:** Data Analytics  
**Task:** Level 1 – Task 2