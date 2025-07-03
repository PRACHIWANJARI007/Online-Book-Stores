#  Online Bookstore SQL Project

This project simulates a basic **Online Bookstore Management System** using SQL. It includes database creation, table setup, data queries, and advanced SQL operations to manage books, customers, and orders efficiently. This project is ideal for learning SQL fundamentals along with practical query writing for data analysis and reporting.


##  Description

The project involves:
- Creating a database `OnlineBooks` with three key tables: `Books`, `Customers`, and `Orders`.
- Running a series of **SQL queries** ranging from basic `SELECT` operations to advanced joins, aggregations, and nested queries.
- Extracting insights such as total revenue, top customers, best-selling genres, stock availability, and much more.


## Key Features

- Manage **Books** (title, genre, author, price, stock, etc.)
-  Handle **Customer Data** (name, email, location)
-  Track **Orders** (order date, quantity, amount)
-  Perform **Data Analysis** such as:
  - Total stock
  - Revenue generation
  - Most popular genres
  - City-based customer spending
  - Most frequent buyers and best-selling books

---

##  Technologies Used

- PostgreSQL (or any SQL-compatible database)
- SQL (DDL + DML + aggregate functions + subqueries + joins)


##  How to Use

1. **Setup the Database**  
   Create the database and tables using the script provided in `SQL Project.sql`.

2. **Insert Sample Data** *(if needed)*  
   You can extend the script with `INSERT` statements for demo/testing purposes.

3. **Run Queries**  
   Execute the SELECT and analysis queries to explore the data and retrieve insights.

4. **Advanced Analysis**  
   Try modifying or extending the queries to create your own reports (e.g., monthly sales reports or stock alerts).


## Sample Queries for your practice
### Basic Queries
1) Retrieve all book in the 'Fiction' genre.
2) Find books published after the year 1950.
3) List all customers from the Canada.
4) Show orders placed in november 2023.
5) Retrive the total stock of books available.
6) Find the details of the most expensive book.
7) Show all customers who ordered more than w quantity of a book.
8) Retrieve all orders where the total amount exceeds $20.
9) List all genres available in the books table.
10) Find the book with the lowest stock.
11) Calculate the total revenue generated from all orders.
### Advance Queries
1) Retrieve the total numbers of books sold for each genre.
2) Find the average price of books in the 'Fantasy' genre.
3) List customers who have placed at least 2 orders.
4) Find the most frequently ordered book.
5) Show the top 3 most expensive books of 'Fantasy'.
6) Retrieve the total quantity of books sokd by each author.
7) List the cites where customers who spent over $30 are located.
8) Find the customer who spent the most on orders.
9) Calculate the stock remaining after fulfillng all orders.
