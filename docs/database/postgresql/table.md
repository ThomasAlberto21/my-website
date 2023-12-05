---
sidebar_position: 11
---

# Table

## See Table

#### How to see table in database PostgreSQL in terminal linux?

you can type following command in terminal

```bash
\dt
```

#### How to see table in database PostgreSQL use DataGrip and terminal linux?

you can type following command

```sql
SELECT * FROM pg_tables WHERE schemaname = 'public';
```

## Create Table

#### How to create table in terminal linux or DataGrip?

you can type following command

```sql
CREATE TABLE barang
(
    kode    INT,
    nama    VARCHAR(100),
    harga   INT,
    jumlah  INT
);
```

## See Structure Table

#### How to see structure table in terminal linux?

you can type following command in terminal

```bash
\d name_table;
```
