# 🧠 Customer Segmentation Project - E-commerce

This project involves customer segmentation using K-Means clustering based on customer transaction behavior. It includes data preprocessing, clustering, evaluation, and a Power BI dashboard for insights visualization.


---

## 🔍 Features Used for Clustering

- `total_transactions`: Number of transactions made by the customer.
- `unique_coupons`: Number of distinct coupons used.
- `burned_coupons`: Number of coupons actually used (burned).

---

## ⚙️ Methodology

- Data merging and preprocessing using pandas.
- Feature scaling using `StandardScaler`.
- K-Means clustering (optimal k determined via Elbow Method).
- Evaluation using `silhouette_score`.
- Cluster analysis and segmentation strategy.

---

## 📈 Visualizations

- Elbow curve to find optimal K.
- Cluster scatterplot.
- Segment-wise statistics using `groupby`.

---

## 🖥️ Dashboard Overview (Power BI)

Here’s a Power BI dashboard created to visually explore key metrics and customer behavior:

![E-commerce Insight](https://github.com/Samar-mohammed/Customer-Segmentation-Project---E-commerce/blob/main/E-commerce.png?raw=true)

### 📊 Highlights:

- **📅 Coupon Usage Over Time**: Shows trends in burned and subscribed coupon usage.
- **🗺️ Coupon Usage by City**: Visualizes usage distribution geographically.
- **📈 Customer Growth Trend**: Analyzes new customers over the years.
- **📦 Top Merchants and Cities**: Based on number of coupon transactions.
- **🧑‍🤝‍🧑 Customer Gender Breakdown**: Distribution of male vs female customers.
- **📋 Customer Coupon Transaction Table**: Displays individual user behavior.

---

## 🧠 Cluster Interpretation & Recommendations

| Cluster | Characteristics | Strategy |
|--------|------------------|----------|
| 0 | High transactions | Reward loyalty with exclusive offers |
| 1 | Many unique coupons | Targeted discounts and cashback |
| 2 | Moderate activity | Personalized recommendations |
| 3 | Low engagement | Win-back campaigns with strong incentives |

---
