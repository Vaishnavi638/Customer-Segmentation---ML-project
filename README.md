# Customer-Segmentation-( Python, K-Means, RFM Analysis, PowerBI)

🔎 **Project Overview**

This project applies RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment customers based on purchasing behavior. The results are visualized using an interactive Power BI dashboard to generate actionable business insights.
The goal of this project is to identify high-value customers, detect churn risks, and support data-driven marketing strategies.

🎯** Problem Statement
**
Businesses often struggle to understand customer behavior and allocate marketing budgets effectively. This project aims to segment customers into meaningful groups using unsupervised learning techniques and provide business intelligence through a dashboard.


📁 **Dataset**

Dataset: Online Retail II (2009–2011)
Source: Kaggle
Contains transactional data including InvoiceNo, CustomerID, Quantity, UnitPrice, and InvoiceDate.


⚙️** Methodology
**
1️⃣ Data Cleaning - 

Removed missing CustomerID values
Removed negative quantities and prices
Created TotalAmount feature

2️⃣ RFM Feature Engineering - 

Recency – Days since last purchase
Frequency – Number of unique purchases
Monetary – Total spending

3️⃣ Data Scaling-

StandardScaler was applied before clustering.

4️⃣ K-Means Clustering-

Elbow Method used to determine optimal clusters (K = 4)
Customers segmented into:
Lost Customers
Occasional Customers
Loyal Customers
Premium Customers

📊 **Power BI Dashboard Features**

KPI Cards (Total Customers, Total Revenue, Avg Recency, Avg Frequency)
Customer Segment Distribution (Donut Chart)
Revenue Contribution by Segment (Bar Chart)
RFM Behavioral Scatter Plot
Segment Comparison Table
Interactive Slicers

💡** Key Business Insights
**
Premium customers contribute the highest revenue.
Loyal customers provide stable repeat purchases.
Lost customers show high churn risk.
Revenue is concentrated among a small percentage of customers.
Targeted marketing strategies can improve retention and profitability.


🛠** Tools & Technologies**

Python (Pandas, NumPy)
Scikit-learn (K-Means, StandardScaler)
Matplotlib / Seaborn
Power BI
DAX

**Business Value**

This project demonstrates how machine learning outputs can be integrated with business intelligence tools to:
Improve customer retention
Optimize marketing budget
Increase customer lifetime value
Support data-driven decision-making


🚀** Conclusion**

The project successfully segments customers using RFM-based clustering and transforms analytical insights into an interactive business dashboard. It highlights the practical application of unsupervised learning in solving real-world business problems.
