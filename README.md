
# E-commerce Transactions Analysis, Lookalike Model, and Customer Segmentation

This repository contains the analysis and solutions for an E-commerce Transactions dataset. The project involves three main tasks: Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation using clustering techniques.

## Dataset Description

The dataset includes three files:

1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

---

## Tasks Overview

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **Objective:** Analyze the dataset to uncover meaningful insights.
- **Deliverables:**
  - Jupyter Notebook: [Jampana_Jagadeesh_EDA.ipynb](./Jampana_Jagadeesh_EDA.ipynb)
  - PDF Report: [Jampana_Jagadeesh_EDA.pdf](./Jampana_Jagadeesh_EDA.pdf)
- **Key Deliverables:**
  - Insights from the dataset (e.g., trends, customer behavior, sales patterns).
  - Visualizations for better understanding.

---

### Task 2: Lookalike Model
- **Objective:** Develop a model to recommend 3 similar customers for a given customer based on profile and transaction history.
- **Deliverables:**
  - Lookalike CSV: [Jampana_Jagadeesh_Lookalike.csv](./Jampana_Jagadeesh_Lookalike.csv)
  - Jupyter Notebook: [Jampana_Jagadeesh_Lookalike.ipynb](./Jampana_Jagadeesh_Lookalike.ipynb)
- **Details:**
  - Recommendations include similarity scores.
  - Output generated for the first 20 customers.

---

### Task 3: Customer Segmentation / Clustering
- **Objective:** Perform customer segmentation using clustering techniques to identify patterns in customer behavior.
- **Deliverables:**
  - Clustering CSV: [Jampana_Jagadeesh_Clustering.csv](./Jampana_Jagadeesh_Clustering.csv)
  - Jupyter Notebook: [Jampana_Jagadeesh_Clustering.ipynb](./Jampana_Jagadeesh_Clustering.ipynb)
  - PDF Report: [Jampana_Jagadeesh_Clustering.pdf](./Jampana_Jagadeesh_Clustering.pdf)
- **Details:**
  - Clustering metrics (e.g., DB Index).
  - Visualizations to represent clusters.

---

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib/Seaborn
- Scikit-learn

---

## Author

**Jagadeesh Jampana**  
[GitHub Profile](https://github.com/Jampana-Jagadeesh)
