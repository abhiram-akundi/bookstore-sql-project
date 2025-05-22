# 📚 Online Book Store – SQL Project

This SQL project analyzes the data of an online bookstore using multiple SQL queries on three interrelated datasets: **Books**, **Customers**, and **Orders**. It covers a wide range of SQL concepts from basic filtering to advanced aggregations and analytics.

---

## 📂 Dataset Overview

The project works with the following CSV files:

- `Books.csv` – Contains details about books (Book_ID, Title, Genre, Price, Stock, Author, Year)
- `Customers.csv` – Information about customers (Customer_ID, Name, Country, City)
- `Orders.csv` – Data about customer purchases (Order_ID, Customer_ID, Book_ID, Quantity, Order_Date)

All tables are connected through common keys: `Book_ID` and `Customer_ID`.

---

## 🧠 SQL Queries

1. Retrieve all books in the "Fiction" genre  
2. Find books published after the year 1950   
3. Show orders placed in November 2023  
4. Retrieve the total stock of books available  
5. Find the details of the most expensive book  
6. Show all customers who ordered more than 1 quantity of a book  
7. Retrieve all orders where the total amount exceeds $20  
8. List all genres available in the Books table  
9. Find the book with the lowest stock  
10. Calculate the total revenue generated from all orders  
11. Retrieve the total number of books sold for each genre  
12. Find the average price of books in the "Fantasy" genre  
13. List customers who have placed at least 2 orders  
14. Find the most frequently ordered book  
15. Show the top 3 most expensive books of the 'Fantasy' genre  
16. Retrieve the total quantity of books sold by each author  
17. List the cities where customers who spent over $30 are located  
18. Find the customer who spent the most on orders  
19. Calculate the stock remaining after fulfilling all orders  

---

## 🛠️ Technologies Used

- **SQL** (MySQL)
- CSV file handling (imported into SQL database)
- SQL functions: `JOIN`, `GROUP BY`, `HAVING`, `ORDER BY`, `COUNT`, `SUM`, `AVG`, `LIMIT`, `DATE_FORMAT`

---

## 📌 Key Learning Outcomes

- Data modeling and relationship mapping using keys.
- Query optimization using advanced SQL features.
- Real-world analytics on customer behavior and sales trends.
---

## 🔗 Author

Abhiram Akundi  
https://github.com/abhiram-akundi
