---
sidebar_position: 14
---

# Where Clause

The `WHERE` clause is used to filter records. The `WHERE` clause is used to extract only those records that fulfill a
specified condition.

How to use `WHERE` clause in PostgreSQL?

you can type following command

```sql

-- Select all records from products table where price is greater than 100
SELECT *
FROM products
WHERE price > 100;

-- Select all records from products table where price is greater than 100 and quantity is greater than 10
SELECT *
FROM products
WHERE price > 100
  AND quantity > 10;

-- Select all records from products table where price is greater than 100 or quantity is greater than 10
SELECT *
FROM products
WHERE price > 100
   OR quantity > 10;

-- Select all records from products table where price is greater than 100 and quantity is greater than 10 and name is not null
SELECT *
FROM products
WHERE price > 100
  AND quantity > 10
  AND name IS NOT NULL;

-- Select all records from products table where price is less than 100 and quantity is less than 10 
SELECT *
FROM products
WHERE price < 100
  AND quantity < 10;
```