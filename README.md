# Customer-Segmentation-and-Transaction-Analysis
Project Summary
This project segments customers from a UK-based online retailer's transaction data to provide actionable business insights. Using the UCI Online Retail dataset, this analysis transforms raw transactional data into meaningful customer profiles to inform targeted marketing and retention strategies.

• Data Aggregation: Transaction data was aggregated to create customer-level features, including total spending (Total_Bill_Size) and purchase frequency   (Purchase_Interval_Days).

• Clustering Models: Both K-Means and DBSCAN algorithms were applied to segment customers. K-Means created broad segments based on spending, while DBSCAN identified natural, density-based clusters and detected outliers.

Key Findings & Analysis

• K-Means Segmentation: Successfully identified three primary customer segments:

  1. Core Customers (4,346): The largest group with moderate spending habits.

  2. Significant Spenders (23): A smaller, high-spending segment.

  3. Top Spenders (3): An elite, extremely high-value group.

• DBSCAN Analysis: Grouped the majority of customers (4,337) into a large, dense cluster, representing typical purchasing behavior. It also isolated smaller, distinct customer groups and identified 12 outliers with anomalous spending patterns.

Business Impact
• The insights from this segmentation allow a business to:

• Develop targeted marketing campaigns for different customer segments (e.g., exclusive offers for top spenders).

• Create tailored customer retention strategies.

• Investigate outliers to understand unique customer behaviors or potential data anomalies.
