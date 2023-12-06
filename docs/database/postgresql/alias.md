---
sidebar_position: 17
---

# Alias

`ALIAS` is a temporary name that is used to rename a table or a column in a table. `ALIAS` is very useful for join
tables

#### How to use alias in PostgreSQL?

you can type following command like this

```sql
-- Example alias column
SELECT id AS Kode, name AS Nama, description AS Deskripsi, price AS Harga, category AS Kategori
FROM products;

-- Example alias table
SELECT p.id AS Kode, p.name AS Nama, p.description AS Deskripsi, p.price AS Harga, p.category AS Kategori
FROM products AS p;
```