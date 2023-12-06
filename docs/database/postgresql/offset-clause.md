---
sidebar_position: 20
---

# Offset Clause

`OFFSET` clause is used to skip the number of rows from the result set returned by the `SELECT` statement. `OFFSET`
clause is used with the `SELECT` statement to skip the number of rows before returning the result set.

#### How to use offset in PostgreSQL?

you can type following command like this

```sql
-- Example offset
SELECT *
FROM products
WHERE price > 0
ORDER BY price DESC OFFSET 2;
```
