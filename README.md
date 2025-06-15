# Sales Trend Analysis Using SQL

This project focuses on analyzing monthly sales trends using SQL with a real-world eCommerce dataset. It demonstrates how to join and aggregate data across multiple tables to generate insights like total revenue and order volume per month.

## 🔍 Objective

To calculate monthly revenue and order volume using SQL by:
- Extracting order dates
- Joining relevant tables (`orders`, `orderitem`, `product`)
- Aggregating revenue and order counts
- Grouping by year and month

## 📁 Project Structure
- data - Contains CSV files for each table
- notebook - Google Colab notebook with SQL + analysis
- output - Final result: monthly summary CSV

## 📊 Dataset Overview

The project uses an eCommerce dataset with the following tables:
- `orders`: order ID, customer ID, and order date
- `orderitem`: quantity and product ID for each order
- `product`: product details with price
- `customer`: customer info (not used directly in this task)

## 🚀 Tools Used

- Google Colab
- SQLite (via Python `sqlite3` library)
- SQL (Joins, Aggregations, Date Functions)
- Pandas for data manipulation and result export

## 📈 Final Output

| order_year | order_month | total_revenue | total_orders |
|------------|-------------|----------------|----------------|
| 2024       | 01          | 1500.00        | 35             |
| 2024       | 02          | 2300.00        | 42             |

## 🛠 How to Use

1. Clone the repository
2. Open the notebook in Google Colab
3. Upload your CSV files (or use provided samples)
4. Run the notebook to generate the monthly sales summary

## 📬 Contact

Created by [Dhana Lakshmi Kotupalli](https://www.linkedin.com/in/dhanalakshmik506)

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
