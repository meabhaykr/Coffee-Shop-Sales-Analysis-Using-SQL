# Coffee Shop Sales Analysis with SQL

Welcome to the Coffee Shop Sales Analysis project! This repository showcases SQL-based data analysis performed on transactional data from a coffee shop. The primary objective is to derive actionable insights from sales data to enhance decision-making processes. The analysis focuses on revenue trends, customer behavior, product performance, and operational efficiency.

---

## **Project Overview**

This project analyzes the sales transactions from a coffee shop, stored in the `Transactions` table. Key insights include total revenue, visitor counts, sales trends, product performance, and store-level analysis. The findings aim to inform business strategies, optimize operations, and improve customer experience.

---

## **Database Schema**

### **Transactions Table**
| Column Name       | Data Type         | Description                                             |
|--------------------|-------------------|---------------------------------------------------------|
| `transaction_id`   | INT               | Unique identifier for each transaction.                |
| `transaction_date` | DATE              | Date of the transaction.                               |
| `transaction_time` | TIME              | Time of the transaction.                               |
| `store_id`         | INT               | Unique identifier for each store.                      |
| `store_location`   | VARCHAR(255)      | Store location name.                                   |
| `product_id`       | INT               | Unique identifier for the product.                     |
| `transaction_qty`  | INT               | Quantity of the product in the transaction.            |
| `unit_price`       | DECIMAL(10, 2)    | Unit price of the product.                             |
| `product_category` | VARCHAR(255)      | Category of the product (e.g., Coffee, Tea).           |
| `product_type`     | VARCHAR(255)      | Type of the product (e.g., Beverage, Snack).           |
| `product_detail`   | VARCHAR(255)      | Specific product name (e.g., Barista Espresso).         |
| `size`             | VARCHAR(50)       | Product size (e.g., Small, Regular, Large).            |
| `amount`           | DECIMAL(10, 2)    | Total amount for the transaction.                      |
| `month_name`       | VARCHAR(255)      | Name of the transaction month.                         |
| `day_name`         | VARCHAR(50)       | Day of the week of the transaction.                    |
| `hour`             | INT               | Hour of the transaction (0–23).                        |
| `day_of_week`      | INT               | Numeric representation of the day (1–7).               |
| `month`            | INT               | Numeric representation of the month (1–12).            |

---

## **Project Objectives**

1. **Revenue Analysis**: Calculate total sales, average transaction values, and average order sizes.  
2. **Visitor Trends**: Identify peak hours, high-performing days, and unique visitor counts.  
3. **Store Performance**: Compare sales performance across store locations.  
4. **Product Insights**: Evaluate product size preferences and identify top-selling items.  
5. **Category Contribution**: Analyze category-wise sales distribution and contributions to total revenue.  
6. **Visualize Trends**: Enable visualization-ready data for further exploration.
---

## **Insights and Recommendations**

1. **Revenue Overview**: Analyze total revenue and average customer spend to track overall business performance.  
2. **Peak Periods**: Use insights from peak hours and high-performing days to improve staffing and inventory allocation.  
3. **Store-Level Performance**: Focus on underperforming stores for optimization and high-performing stores for replicable strategies.  
4. **Product Preferences**: Highlight popular products and sizes for better inventory planning and menu optimization.  
5. **Category Contributions**: Allocate marketing resources based on category-wise revenue contributions.

---

## **Future Enhancements**

1. **Predictive Analysis**: Implement machine learning models for forecasting sales trends.  
2. **Customer Insights**: Integrate demographic data to understand and segment customer behavior.  
3. **Real-Time Dashboards**: Leverage visualization tools like Tableau or Power BI for real-time insights.

---

## **Getting Started**

1. Clone the repository:  
   ```bash
   git clone https://github.com/meabhaykr/Coffee-Shop-Sales-Analysis-Using-SQL
   ```
2. Load the sample database schema and data into your preferred SQL environment.  
3. Run the SQL scripts provided to explore insights.
