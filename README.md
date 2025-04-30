# 📚 Online Bookstore Data Analysis using SQL

🎯 **Project Title:** SQL Project – Online Bookstore Analysis  
🗂️ **Datasets Used:** `Books.csv`, `Customers.csv`, `Orders.csv`  
🎓 **Focus:** SQL-based data extraction, transformation, and business insight generation

---

## 🧾 Project Overview

This project simulates a real-world business analysis case study for an **Online Bookstore**. Using SQL and PostgreSQL, I worked with three interconnected datasets to extract meaningful insights regarding sales performance, inventory tracking, and customer activity.

### 📦 Datasets:

- **📘 Books.csv** – Details about book inventory (titles, authors, prices, genres, stock)
- **👥 Customers.csv** – Information about registered customers (location, contact details)
- **🛒 Orders.csv** – Transaction history of book purchases (dates, quantities, total amounts)

The goal was to explore these datasets with SQL and answer practical business questions relevant to the e-commerce domain.

---

## 🗃️ Database Schema

| Books.csv         | Customers.csv       | Orders.csv           |
|-------------------|---------------------|-----------------------|
| `Book_ID` (PK)     | `Customer_ID` (PK)   | `Order_ID` (PK)        |
| `Title`            | `Name`               | `Book_ID` (FK)         |
| `Author`           | `Email`              | `Customer_ID` (FK)     |
| `Genre`            | `Phone`              | `Order_Date`           |
| `Published_Year`   | `City`               | `Quantity`             |
| `Price`            | `Country`            | `Total_Amount`         |
| `Stock`            |                     |                       |

---

## 🔍 SQL Query Summary

### 🟢 **Basic Queries**

- Retrieve all books in the "Fiction" genre  
- Find books published after 1950  
- List all customers from Canada  
- Show orders placed in November 2023  
- Get the total stock of books  
- Identify the most expensive book  
- Find customers who ordered more than one unit  
- Fetch orders with total amount > $20  
- List all unique genres in the inventory  
- Find the book with the lowest stock  
- Calculate total revenue generated  

### 🔵 **Advanced Queries**

- Count books sold by each genre  
- Average price of books in the "Fantasy" genre  
- Customers with at least 2 orders  
- Most frequently ordered book  
- Top 3 most expensive Fantasy books  
- Books sold by each author  
- Cities with customers who spent over $30  
- Highest-spending customer  
- Remaining stock after fulfilling orders  

---

## 📊 Insights & Observations

- **📈 Fiction and Fantasy** were the most frequently purchased genres, indicating high demand in these categories.
- **💰 Revenue Generation:** The total revenue from all orders provides a strong indicator of sales success and can be monitored monthly.
- **🧍‍♂️ High-Value Customers:** A few customers placed multiple orders and spent significantly, making them prime candidates for loyalty rewards or personalized marketing.
- **🔖 Top-Selling Book:** One book stands out as the most frequently ordered, potentially suitable for featured promotions or bundling strategies.
- **📉 Inventory Imbalance:** Certain books have very low stock despite high sales, indicating a need for restocking or demand forecasting.
- **🌍 Customer Geography:** High-value customers are spread across various cities, but some locations show higher average spending, useful for regional targeting.
- **📚 Author Performance:** Some authors drive higher sales volumes, suggesting the possibility of stocking more titles from them.
- **📊 Price Sensitivity:** The average price analysis of genres like Fantasy shows variability, useful for adjusting pricing models or discounts.

---

## 🛠 Tools & Technologies Used

- **💻 PostgreSQL** – SQL query execution  
- **🧠 SQL** – Joins, GROUP BY, HAVING, Subqueries, Filtering, Date functions  
- **📊 CSV Files** – As relational database tables  
- **📁 Git & GitHub** – Version control and collaboration  

---

## 📂 Repository Structure

| File                        | Description                                      |
|-----------------------------|--------------------------------------------------|
| `OnlineBookStore Analysis.sql` | Complete SQL scripts used for analysis           |
| `Books.csv`                  | Book inventory dataset                          |
| `Customers.csv`              | Customer information dataset                    |
| `Orders.csv`                 | Purchase history dataset                        |
| `OnlineBookStore Analysis.pdf` | Final report of all SQL queries (PDF format)     |
| `README.md`                  | Project documentation (this file)              |

---

## 🎓 Key Learnings

- Gained experience working with normalized relational datasets  
- Improved SQL fluency in real-world scenarios  
- Applied multi-table joins and aggregation techniques  
- Simulated business reporting tasks in a retail data environment  
- Strengthened analytical thinking around customer and inventory metrics  

---

## 🔗 Connect with Me

**👤 Name:** Dolly Gupta 
**🌐 LinkedIn:** https://www.linkedin.com/in/dolly-gupta-3b54b8229 
**📬 dollygupta362@gmail.com
---
