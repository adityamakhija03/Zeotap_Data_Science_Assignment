# eCommerce Transactions Analysis and Modeling

This repository contains an end-to-end data analysis and machine learning project built around an eCommerce Transactions dataset. The project focuses on exploratory data analysis (EDA), predictive modeling, and customer segmentation to generate actionable business insights.

---

## Dataset Overview
The dataset includes three files:

1. **Customers.csv**
   - **CustomerID**: Unique identifier for each customer.  
   - **CustomerName**: Name of the customer.  
   - **Region**: Continent where the customer resides.  
   - **SignupDate**: Date when the customer signed up.  

2. **Products.csv**
   - **ProductID**: Unique identifier for each product.  
   - **ProductName**: Name of the product.  
   - **Category**: Product category.  
   - **Price**: Product price in USD.  

3. **Transactions.csv**
   - **TransactionID**: Unique identifier for each transaction.  
   - **CustomerID**: ID of the customer who made the transaction.  
   - **ProductID**: ID of the product sold.  
   - **TransactionDate**: Date of the transaction.  
   - **Quantity**: Quantity of the product purchased.  
   - **TotalValue**: Total value of the transaction.  
   - **Price**: Price of the product sold.  

---

## Project Tasks

### 1. Exploratory Data Analysis (EDA) and Business Insights
- Perform detailed EDA to uncover patterns in customer behavior, product sales, and transaction trends.  
- Derive at least 5 actionable business insights from the dataset.
- **Outputs:** Jupyter Notebook (EDA code) and a concise PDF report summarizing the insights.

### 2. Lookalike Model
- Develop a machine learning model to recommend 3 similar customers based on a user's profile and transaction history.  
- Combine customer and product information for better predictions.
- **Outputs:**
  - CSV file mapping CustomerID to their top 3 lookalikes with similarity scores.
  - Jupyter Notebook explaining model development.

### 3. Customer Segmentation / Clustering
- Apply clustering techniques to segment customers using both profile and transaction data.  
- Evaluate cluster quality using Davies-Bouldin Index (DB Index) and other clustering metrics.
- Visualize the clusters for better interpretation.
- **Outputs:** Clustering metrics, visualizations, and a detailed report.

---

## Deliverables
- **Notebooks:** EDA, Lookalike Model, and Clustering notebooks.
- **Reports:** PDF files summarizing insights and clustering results.
- **Results:** CSV files containing model outputs and mappings.

---

## Evaluation Metrics

- **Lookalike Model:** Accuracy, similarity scores, and quality of recommendations.
- **Clustering:**
  - **Davies-Bouldin Index (DB Index):** Measures cluster compactness and separation (lower is better).
  - **Silhouette Score:** Measures intra-cluster cohesion and inter-cluster separation (higher is better).
  - Visual representations of clusters.

---

## Contact
For questions or feedback, feel free to reach out to [aditya3makhija@gmail.com].
