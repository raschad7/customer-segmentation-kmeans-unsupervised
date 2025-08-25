\# 🛍 Customer Segmentation using K-Means  



\## 📌 Project Overview  

This project applies \*\*unsupervised machine learning\*\* to perform \*\*customer segmentation\*\* using the popular \*\*Mall Customers dataset\*\* (Kaggle).  

The goal is to identify distinct groups of customers based on their \*\*Annual Income\*\* and \*\*Spending Score\*\*, which can help businesses design targeted marketing strategies, loyalty programs, and personalized offers.  



---



\## 🛠 Tools \& Libraries  

\- \*\*Python\*\*  

\- \*\*Pandas, NumPy\*\* → Data handling  

\- \*\*Matplotlib, Seaborn\*\* → Visualization  

\- \*\*Scikit-learn\*\* → Preprocessing, Clustering (K-Means, DBSCAN)  



---



\## 📊 Workflow  



\### 1. Data Loading  

\- Dataset: \*\*Mall\_Customers.csv\*\* (200 rows × 5 columns).  

\- Columns: `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`.  

\- No missing values.  



\### 2. Data Exploration (EDA)  

\- Visualized distributions of \*\*Income\*\* and \*\*Spending Score\*\*.  

\- Scatterplots showed natural groupings in Income vs Spending.  

\- Gender distribution was explored to understand customer demographics.  



\### 3. Preprocessing  

\- Selected features: \*\*Annual Income (k$)\*\* and \*\*Spending Score (1-100)\*\*.  

\- Applied \*\*StandardScaler (Z-score standardization)\*\* to normalize features.  



\### 4. Finding Optimal Clusters  

\- \*\*Elbow Method\*\* → best at \*\*K=5\*\*.  

\- \*\*Silhouette Score\*\* ≈ 0.5 (fair cluster quality).  



\### 5. K-Means Clustering  

\- Applied K-Means with \*\*5 clusters\*\*.  

\- Visualized clusters and centroids.  

\- Labeled segments:  

&nbsp; - Cluster 0 → Budget Customers (low income, low spending)  

&nbsp; - Cluster 1 → Value Shoppers (low income, high spending)  

&nbsp; - Cluster 2 → Average Customers (mid income, mid spending)  

&nbsp; - Cluster 3 → Careful Spenders (high income, low spending)  

&nbsp; - Cluster 4 → Luxury Shoppers (high income, high spending)  



\### 6. Gender Analysis per Cluster  

\- Examined gender distribution inside each cluster.  

\- Example insight: Cluster 0 (Budget Customers) is the largest with a balanced male-female mix, while other clusters showed different gender proportions.  

\- This helps align \*\*marketing strategies\*\* with both \*\*behavior\*\* and \*\*demographics\*\*.  



\### 7. Bonus: DBSCAN  

\- Tried DBSCAN (density-based clustering).  

\- Results were less meaningful (most customers lumped into one big cluster).  

\- Confirmed that \*\*K-Means is more effective\*\* for this dataset.  



---



\## 📈 Results \& Insights  

\- Customers can be grouped into \*\*5 meaningful clusters\*\*.  

\- Each cluster corresponds to a \*\*distinct profile\*\* useful for business decisions.  

\- Gender breakdown per cluster provides additional actionable insights.  

\- Demonstrated the strength of \*\*K-Means for customer segmentation\*\*.  



---



\## 🔮 Conclusion  

Clustering transformed raw customer data into \*\*actionable business intelligence\*\*.  

K-Means provided 5 clear customer segments that can guide targeted strategies, improve customer engagement, and support data-driven decision making.  

Gender distribution analysis further enriched the insights.  



---



\## 📂 Repository Structure  



