📊 **Customer Segmentation Using K-Means**

🎯 **Business Problem**

The marketing team wants to improve campaign effectiveness by identifying distinct customer groups instead of sending generic promotions to all customers. 
This project applies unsupervised learning (K-Means clustering) to segment customers based on income and spending behavior.

📁 **Dataset**
- Mall Customers dataset containing:
- Age
- Gender
- Annual Income (k$)
- Spending Score (1–100)

🧠 **Methodology**
- Selected features: Annual Income & Spending Score
- Scaled data using StandardScaler
- Used Elbow Method to determine optimal number of clusters
- Applied K-Means clustering

📈 **Results**
The model identified 5 customer segments:
- High Income – High Spending (Premium Customers)
- High Income – Low Spending (Upselling Opportunity)
- Low Income – High Spending (Value Loyal Customers)
- Low Income – Low Spending (Low Engagement Segment)
- Mid Income – Moderate Spending (Average Customers)

📌 **Marketing Insights**
- Customer segmentation enables:
- Targeted marketing campaigns
- Personalized promotions
- Improved resource allocation
- Higher engagement potential

🛠 **Tools Used**
Python
Pandas
Matplotlib
Scikit-learn
