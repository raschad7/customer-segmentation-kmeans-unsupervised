# 🛍 Customer Segmentation using K-Means  

![Python](https://img.shields.io/badge/Python-3.10-blue) 
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow) 
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview  
This project applies **unsupervised machine learning** to perform **customer segmentation** using the popular **Mall Customers dataset** (Kaggle).  

The goal is to identify distinct groups of customers based on their **Annual Income** and **Spending Score**, which can help businesses design **targeted marketing strategies, loyalty programs, and personalized offers**.  

---

## 🛠 Tools & Libraries  
- 🐼 **Pandas, NumPy** → Data handling  
- 📊 **Matplotlib, Seaborn** → Visualization  
- 🤖 **Scikit-learn** → Preprocessing & Clustering (K-Means, DBSCAN)  

---

## 📊 Workflow  

### 🔹 1. Data Loading  
- Dataset: **Mall_Customers.csv** (200 rows × 5 columns).  
- Columns: `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`.  
- No missing values.  

### 🔹 2. Data Exploration (EDA)  
- Scatterplot of **Income vs Spending** revealed natural clusters.  
- Gender distribution analyzed with boxplots.  


### 🔹 3. Preprocessing  
- Selected features: **Annual Income (k$)** and **Spending Score (1-100)**.  
- Applied **StandardScaler (Z-score standardization)** to normalize features.  

### 🔹 4. Finding Optimal Clusters  
- **Elbow Method** → best at **K=5**.  
- **Silhouette Score** ≈ 0.5 (fair quality).  



### 🔹 5. K-Means Clustering  
- Applied K-Means with **5 clusters**.  
- Cluster centers plotted.  



| Cluster | Profile | Description |
|---------|----------|-------------|
| 0 | 🟠 Budget Customers | Low income, low spending |
| 1 | 🟢 Value Shoppers | Low income, high spending |
| 2 | 🔴 Average Customers | Mid income, mid spending |
| 3 | 🟣 Careful Spenders | High income, low spending |
| 4 | 🔵 Luxury Shoppers | High income, high spending |

### 🔹 6. Gender Analysis per Cluster  
- Gender distribution analyzed across clusters.  



---

## 📈 Results & Insights  
- Customers grouped into **5 meaningful clusters**.  
- Each cluster corresponds to a **distinct profile** useful for business strategy.  
- Gender breakdown per cluster adds **demographic insight**.  
- K-Means outperformed DBSCAN for this dataset.  

---

## 🔮 Conclusion  
Clustering transformed raw customer data into **actionable business intelligence**.  
K-Means provided **5 clear customer segments** that can guide **marketing strategies, customer engagement, and growth planning**.  
Gender analysis further enriched insights, showing how **demographics interact with spending behavior**.  

---


