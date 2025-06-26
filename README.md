# Customer-segmentation-on-retail-dataset using RFM analysis
This project performs customer segmentation on a retail dataset using RFM (Recency, Frequency, Monetary) analysis. RFM is a widely used marketing technique to identify and categorize customers based on their purchasing behavior. The insights derived help businesses tailor personalized marketing strategies and improve customer retention.

📊 Overview
Goal: Segment customers into distinct groups based on their purchasing patterns to enable targeted marketing and strategic decision-making.

Techniques Used:

Data Cleaning & Preprocessing
RFM Scoring
Customer Segmentation (Manual Thresholding)
Data Visualization

🧰 Tools & Technologies
Python
Pandas
NumPy
Matplotlib / seaborn
Jupyter Notebook

📁 Dataset
The dataset used is a Retail transactional dataset containing:
InvoiceNo
StockCode
Description
Quantity
InvoiceDate
UnitPrice
CustomerID
Country 

You can use public datasets like the Online Retail Dataset from the UCI ML repository.

📈 RFM Metrics
RFM segments customers based on:
Recency: How recently a customer made a purchase.
Frequency: How often a customer makes a purchase.
Monetary: How much money a customer spends.

Each metric is scored and combined to identify customer segments like:
Champions
Loyal Customers
Potential Loyalists
At Risk
Need Attention
At Lost

🔍 Key Steps
Data Cleaning: Handling nulls, duplicates, negative values.
RFM Calculation: Compute Recency, Frequency, Monetary values for each customer.
Scoring & Segmentation: Assign RFM scores and segment customers.
Visualization: Charts and plots to analyze customer segments.

📊 Visuals & Insights
Bar charts for segment distribution
Scatter plots for clustering
