# Customer Segmentation Analysis

## Project Overview
This project aims to segment customers based on their purchasing behavior using unsupervised learning techniques. By analyzing customer data from an online retail platform, the goal is to identify distinct customer segments that can inform targeted marketing strategies.

## Dataset
The dataset used in this project is the **Online Retail Dataset**, which contains transactional data from a UK-based online retailer. The dataset includes the following columns:
- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Unique identifier for each product.
- **Description**: Product description.
- **Quantity**: Number of items purchased.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per item.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Country of the customer.

### Data Source
The dataset was obtained from Kaggle: [Online Retail Dataset](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset).

## Methodology
The project follows these main steps:
1. **Data Preprocessing**: Clean the dataset by handling missing values, converting data types, and standardizing features.
2. **Exploratory Data Analysis (EDA)**: Analyze the data to understand customer purchasing patterns and visualize key metrics.
3. **Feature Engineering**: Create relevant features for clustering, including total spending, number of transactions, and average basket size.
4. **Clustering**: Apply K-Means clustering to segment customers into distinct groups.
5. **Cluster Analysis**: Analyze and visualize the characteristics of each customer segment.
6. **Insights and Recommendations**: Provide actionable recommendations based on the segmentation analysis.

## Key Findings
- **High Spenders**: Customers who spend significantly more and purchase frequently.
- **Occasional Buyers**: Moderate spenders with infrequent purchases.
- **Loyal Customers**: Frequent purchasers with lower average spending.
- **New Customers**: Recently acquired customers with low transaction volume.

## Recommendations
- **High Spenders**: Target with exclusive offers on premium products.
- **Occasional Buyers**: Encourage repeat purchases through loyalty programs and discount codes.
- **Loyal Customers**: Provide personalized product recommendations to enhance shopping experience.
- **New Customers**: Use onboarding campaigns and welcome discounts to increase engagement.

## Visualizations
The project includes several visualizations to depict customer segments and their characteristics, making it easier to communicate findings and recommendations.
