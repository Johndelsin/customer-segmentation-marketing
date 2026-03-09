📊 **Customer Segmentation Using K-Means**

🎯 **Business Problem**

Marketing teams often send the same promotional campaigns to all customers, which can reduce engagement and marketing efficiency. Customer segmentation helps businesses group customers with similar characteristics so that marketing strategies can be more targeted.

This project applies unsupervised machine learning techniques to segment customers based on demographic and spending behavior.

📁 **Dataset**
The dataset contains information about mall customers, including:

- Age
- Gender
- Annual Income (k$)
- Spending Score (1–100)

The **Spending Score** is a metric assigned by the mall based on customer purchasing behavior and spending patterns.

🧠 **Methodology**
The following steps were performed in the analysis:

1. Data inspection and quality checks
2. Feature selection (Age, Income, Spending Score)
3. Feature scaling using StandardScaler
4. Identification of optimal clusters using the Elbow Method
5. Customer segmentation using multiple clustering algorithms:
  K-Means Clustering
  Gaussian Mixture Models (GMM)
  Hierarchical Clustering
  DBSCAN
6. Cluster evaluation using the Silhouette Score

📈 **Results**
The analysis identified five main customer segments based on income and spending behavior:

- High Income – High Spending
  High-value customers who contribute significantly to revenue.

- High Income – Low Spending
  Customers with strong purchasing power but lower engagement.

- Low Income – High Spending
  Customers who actively purchase despite lower income levels.

- Low Income – Low Spending
  Price-sensitive customers with lower engagement.

- Moderate Income – Moderate Spending
  Average customers representing a large portion of the customer base.

📌 **Marketing Insights**
Customer segmentation allows businesses to design more effective marketing strategies, including:

- Targeted marketing campaigns
- Personalized promotions
- Loyalty programs for high-value customers
- Promotional strategies for price-sensitive segments

These insights help improve customer engagement and marketing efficiency.

🛠 **Tools Used**
Python
Pandas
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
