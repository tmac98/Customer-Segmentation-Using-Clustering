# **Customer Segmentation Using Clustering**

## 📌 Project Overview  
This project applies **unsupervised machine learning** techniques to segment customers based on their purchasing behaviour. Using **K-Means and Hierarchical Clustering**, customers are grouped based on **frequency, recency, customer lifetime value (CLV), customer age and average unit cost,** to uncover distinct customer personas. The analysis helps refine marketing strategies by identifying key customer groups.

## 📊 Key Features  
- **🔍 Data Preprocessing:** Cleaning, handling missing values, and feature engineering.  
- **📈 Clustering Techniques:** Implemented **K-Means and Hierarchical Clustering** to segment customers.  
- **📌 Optimal K Selection:** Used **Elbow Method and Silhouette Score** to determine the best number of clusters.  
- **🧠 Dimensionality Reduction:** Applied **PCA and t-SNE** to visualise high-dimensional data in 2D.  
- **📑 Customer Insights:** Profiled customer segments based on spending habits, engagement levels, and age distribution.  

## 📈 Results & Insights  
The analysis identified **five customer segments** with distinct purchasing patterns:

1️⃣ **Loyal, Frequent Buyers** – Moderate spending, highly engaged.  
2️⃣ **Premium Buyers** – Less frequent but high-value purchases.  
3️⃣ **Young, High-Engagement Customers** – Frequent, mid-range spending, typically younger.  
4️⃣ **High-Value Customers** – Frequent, high-spending segment, older and more established.  
5️⃣ **Dormant Customers** – Low engagement, at risk of churn.  

📌 **Silhouette Score and Elbow Method** confirmed that **K=5** was the best choice for clustering.

## 📂 Project Files  
📄 **[Jupyter Notebook: Customer Segmentation Using Clustering](./Customer_Segmentation_Notebook.ipynb)**  
📑 **[Detailed Report: Customer Segmentation Using Clustering](./Customer%20Segmentation%20Report.pdf)**  

## 🛠 Technologies Used  
- 🐍 **Python:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib  
- 🧠 **Machine Learning:** K-Means, Hierarchical Clustering, PCA, t-SNE  
- 📊 **Data Visualisation:** Boxplots, Clustering Scatter Plots  

## 🔮 Future Improvements  
- **📊 Explore alternative clustering methods** (e.g., DBSCAN, Gaussian Mixture Models).  
- **📈 Add more customer metrics** (e.g., retention rate, engagement scores).  
- **🖥️ Deploy as an interactive dashboard** for business users.  
