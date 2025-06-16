# 🧠 Customer Segmentation using K-Means

This project uses clustering techniques to segment mall customers based on their income and spending patterns. The goal is to help businesses understand customer behavior and tailor marketing strategies accordingly.

## 📌 Project Objective:
Segment customers into distinct groups using unsupervised machine learning (K-Means), based on attributes such as annual income and spending score.

## 📂 Dataset

1. Mall_Customers_Segments.csv
2. 200+ records of customer demographics:
CustomerID, Gender, Age, Annual Income, Spending Score

## 🔍 Problem Statement:
“How can we group similar customers together based on their spending behavior and income levels, so that businesses can tailor their offerings?”

## 📊 Key Steps: 
1. Data Cleaning & Visualization
2. Checked distributions and outliers in income and spending score.
3. Visualized gender and age group balances.
4. Optimal Clusters Selection
5. Used the Elbow Method to determine ideal k.
6. Chose 5 clusters based on inertia and visual elbow.
7. K-Means Clustering
8. Applied K-Means to cluster customers by spending vs income.
9. Labeled each customer with their respective cluster.
10. Cluster Interpretation: 

Cluster 1: High spenders with moderate income

Cluster 2: High income, low spenders

Cluster 3: Balanced customers

Cluster 4: Low income, low spenders

Cluster 5: High income, high spenders

## 🧰 Tools & Libraries

Python 3
Pandas, NumPy
Seaborn, Matplotlib
Scikit-learn (KMeans)

## 📸 Key Visuals

2D scatter plot of clusters (spending score vs income)

![image alt](https://github.com/GauravLayak/Customer-Segmentation/blob/35338acf5c15a5b2cb82d15bbd164a82067e2f7e/scatter%20plot.png)


## ✅ Business Insights

1. Cluster-based marketing can improve targeting and reduce ad spend.
2. High-income low-spenders may need retention offers or new luxury options.
3. Balanced customers represent safe, long-term revenue channels.
4. Low spenders could be ignored or targeted with budget-friendly offers.


## 🚀 What I Learned

How to apply K-Means for business segmentation

The value of preprocessing and feature scaling in unsupervised ML

Real-world interpretation of abstract clusters
