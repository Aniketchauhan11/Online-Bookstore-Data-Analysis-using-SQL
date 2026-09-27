# Online-Bookstore-Data-Analysis-using-SQL
SQL-based analysis of an online bookstore dataset using relational tables, joins, aggregations, filtering, grouping, and analytical queries.

## 🚀 Project Overview

This project demonstrates the use of SQL to manage and analyze an online bookstore database containing information about books, customers, and orders.

The database consists of three related tables:

- Books
- Customers
- Orders

The project covers database creation, table design, data import, basic SQL queries, advanced analytical queries, joins, filtering, grouping, aggregation, and inventory analysis.

## 🎯 Project Objective

The objective of this project is to analyze bookstore data and extract useful information related to:

- Book inventory
- Book genres and pricing
- Customer information
- Orders and quantities
- Revenue
- Customer spending
- Book sales by genre and author
- Remaining stock

## 🗄️ Database Structure

### Books
Contains book-level information including:

- Book ID
- Title
- Author
- Genre
- Published Year
- Price
- Stock

### Customers
Contains customer information including:

- Customer ID
- Name
- Email
- Phone
- City
- Country

### Orders
Contains transaction-level information including:

- Order ID
- Customer ID
- Book ID
- Order Date
- Quantity
- Total Amount

The Orders table connects customers and books using Customer_ID and Book_ID relationships.

## 🛠️ Tools & Technologies

- PostgreSQL
- SQL
- Relational Database
- Data Analysis
- Aggregate Functions
- JOIN Operations

## 🔍 SQL Concepts Used

- SELECT
- WHERE
- DISTINCT
- ORDER BY
- LIMIT
- BETWEEN
- SUM()
- AVG()
- COUNT()
- GROUP BY
- HAVING
- INNER JOIN
- LEFT JOIN
- COALESCE()
- Primary Keys
- Foreign Keys

## 📊 Analysis Performed

### Basic Analysis

- Retrieved books from the Fiction genre.
- Identified books published after 1950.
- Retrieved customers from Canada.
- Analyzed orders placed during November 2023.
- Calculated total available book stock.
- Identified the most expensive book.
- Retrieved orders with quantities greater than one.
- Identified orders with total amounts above $20.
- Listed available book genres.
- Identified the book with the lowest stock.
- Calculated total revenue from orders.

### Advanced Analysis

- Calculated total books sold by genre.
- Calculated average book price for the Fantasy genre.
- Identified customers with at least two orders.
- Identified the most frequently ordered book.
- Retrieved the top three most expensive Fantasy books.
- Calculated total books sold by each author.
- Identified cities associated with customers spending over $30.
- Identified the customer with the highest total spending.
- Calculated remaining stock after fulfilling orders.

## 💡 Key SQL Analysis

The project uses JOIN operations to combine customer, book, and order information and aggregation functions such as SUM(), AVG(), and COUNT() to generate analytical results.

GROUP BY and HAVING are used to perform grouped analysis and identify customers, genres, authors, and other categories meeting specific conditions.

LEFT JOIN and COALESCE() are used for inventory analysis to calculate remaining stock, including books with no associated orders.

## 📈 Project Outcome

Successfully created and analyzed a relational bookstore database using SQL.

The project demonstrates practical experience in database creation, data querying, relational joins, aggregation, filtering, grouping, and extracting business-oriented insights from transactional data.

## 📂 Project Files

- SQL query file
- Books dataset
- Customers dataset
- Orders dataset
- Project documentation
