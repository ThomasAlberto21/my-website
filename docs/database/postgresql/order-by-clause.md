---
sidebar_position: 18
---

# Order By Clause

`ORDER BY` clause is used to sort the result-set in ascending or descending order. `ORDER BY` clause sorts the records
in
ascending order by default. To sort the records in descending order, use the `DESC` keyword.

#### How to use order by in PostgreSQL?

you can type following command like this

```sql
-- Example order by

-- Example order by asc
SELECT *
FROM products
ORDER BY id ASC;

SELECT *
FROM products
ORDER BY price ASC, id DESC;

-- Example order by desc
SELECT *
FROM products
ORDER BY id DESC;

SELECT *
FROM products
ORDER BY price DESC, id ASC;
```