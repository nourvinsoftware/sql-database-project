# SQL Database Project

A database project created to practice SQL fundamentals, data management and database design.

## Features

- Create tables
- Insert data
- Update records
- Delete records
- SQL JOIN queries
- GROUP BY
- HAVING
- Aggregate functions

## Technologies Used

- SQL
- MySQL
- Git
- GitHub

## Database Structure

```sql
Customers
Orders
Products
Employees
```

## Skills Demonstrated

- Database design
- Data normalization
- Query optimization
- Data analysis
- Relational databases

## Example Query

```sql
SELECT customers.name,
       orders.order_date
FROM customers
INNER JOIN orders
ON customers.id = orders.customer_id;
```
