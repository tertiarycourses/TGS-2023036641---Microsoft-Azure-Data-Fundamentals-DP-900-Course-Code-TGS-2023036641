# Lab 03 - Relational Data, SQL, Normalization, Database Objects

## Objectives

- Explain relational data concepts.
- Identify tables, rows, columns, keys, and relationships.
- Understand normalization.
- Recognize common SQL statements and database objects.

## Scenario

The retail company stores customers, orders, products, and order lines in a relational database. You must explain how the data is structured and queried.

## Steps

### 1. Draw a Relational Model

Create entities:

```text
Customers
Orders
OrderItems
Products
```

Add primary keys and foreign keys.

### 2. Explain Normalization

Answer:

1. Why should product data not be repeated on every order line?
2. How do separate tables reduce update errors?
3. What is the tradeoff of normalization?

### 3. Identify SQL Statement Types

Create a table:

| SQL Statement | Purpose |
| --- | --- |
| SELECT | Read data |
| INSERT | Add data |
| UPDATE | Modify data |
| DELETE | Remove data |
| CREATE | Create objects |

### 4. Review Database Objects

Define:

```text
Table
View
Index
Stored procedure
Schema
Primary key
Foreign key
```

### 5. Write Example Queries

```sql
SELECT ProductName, Price
FROM Products;
```

```sql
SELECT c.CustomerName, o.OrderDate
FROM Customers c
JOIN Orders o ON c.CustomerID = o.CustomerID;
```

## Validation

You should have a relational diagram, normalization notes, SQL table, object definitions, and example queries.

## Checkpoint Questions

1. What is a primary key?
2. What is a foreign key?
3. Why is normalization used?
4. What does SELECT do?

## Exam Focus

DP-900 expects recognition of relational concepts and common SQL statements, not advanced SQL programming.
