# 🛍️ Customer Segmentation using K-Means Clustering

This project performs customer segmentation on a mall dataset using **K-Means Clustering**. It helps businesses understand customer behavior based on **Annual Income** and **Spending Score**, aiding in targeted marketing strategies.

---

## 📁 Dataset

- **Source**: [Mall_Customers.csv](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- The dataset contains basic information about mall customers:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 📊 Techniques Used

- Exploratory Data Analysis (EDA)
- Data Standardization with `StandardScaler`
- K-Means Clustering (`sklearn`)
- Elbow Method to find optimal K
- Cluster visualization with `seaborn` and `matplotlib`

---

## 📌 Project Highlights

- **EDA** to understand income and spending patterns
- **Elbow Method** to determine the optimal number of clusters
- **Customer segmentation** into 5 distinct groups
- **Visual representation** of clusters and centroids
- **Cluster summary** to extract actionable business insights

---

## 🧠 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
sklearn
