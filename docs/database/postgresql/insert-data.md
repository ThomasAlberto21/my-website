---
sidebar_position: 12
---

# Insert Data

#### How to insert data in table use PostgreSQL?

you can type following command

```sql
-- Before insert data, you must create table
CREATE TABLE products
(
    id          VARCHAR(10)  NOT NULL,
    name        VARCHAR(100) NOT NULL,
    description TEXT,
    price       INT          NOT NULL,
    quantity    INT          NOT NULL DEFAULT 0,
    created_at  TIMESTAMP    NOT NULL DEFAULT CURRENT_TIMESTAMP
);

-- Insert data
INSERT INTO products (id, name, description, price, quantity)
VALUES ('P0001', 'Mie Ayam', 'Mie Ayam Enak', 100, 10),
       ('P0002', 'Teh ES', 'Teh Es Enak', 200, 20),
       ('P0003', 'Bakso', 'Bakso Ayam', 300, 30),
       ('P0004', 'Nasi Goreng', 'Nasi Goreng Ayam', 400, 40),
       ('P0005', 'Soto', 'Soto Ayam', 500, 50);
```
