# E-Commerce Dataset Analysis using SQL

##  Project Overview
This project analyzes the **Olist E-Commerce Dataset** to uncover insights about sales trends, customer behavior, and product performance.  
The analysis is performed using **SQL queries** on an **SQLite database**, with results and visualizations generated in a Jupyter Notebook.

##  Dataset
- **Source**: [Kaggle - E-Commerce Dataset by Olist](https://www.kaggle.com/datasets/terencicp/e-commerce-dataset-by-olist-as-an-sqlite-database)
- **Content**: Orders, Products, Sellers, Customers, Reviews, and related attributes.
- **Format**: SQLite database.

##  Project Steps
1. Load the dataset into SQLite.
2. Explore the database schema and tables.
3. Answer 12 business-focused questions using SQL queries.
4. Visualize and interpret the findings.

##  Business Questions Answered
The project answers the following key questions:

1. **What are the best-selling product categories by quantity and revenue?**
2. **What is the distribution of orders by customer location (state and city)?**
3. **What is the average delivery time, and how does it vary across states?**
4. **What is the relationship between product price and freight cost?**
5. **What are the top reasons for customer complaints in low-rated reviews (score ≤ 2)?**
6. **What are the most popular payment methods among customers, and how does payment method preference vary by region?**
7. **Which products have the highest return rates based on reviews or order cancellations?**
8. **What is the average review score by product category?**
9. **What is the correlation between order value and review score?**
10. **How does seller performance (delivery delay, cancellations) affect customer satisfaction?**
11. **What is the contribution of different sellers to total sales?**
12. **How do customer buying patterns vary across different times (e.g., months or seasons)?**

##  Technologies Used
- **SQLite** for database management
- **SQL** for querying
- **Python** (Jupyter Notebook) for analysis
- **Pandas** for data manipulation
- **Matplotlib / Seaborn** for data visualization

##  How to Run Locally
1. Clone this repository.
2. Install required packages:
   ```bash
   pip install pandas matplotlib sqlite3
