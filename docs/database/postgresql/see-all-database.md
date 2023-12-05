---
sidebar_position: 3
---

# See All Database PostgreSQL

#### How to see list database PostgreSQL in linux terminal?

To display a list of existing databases along with additional information such as owner, encoding, and access granted you can type following comand in terminal

```bash
\l
```

#### For only see database, you can type following command in terminal

```bash
select datname from pg_database;
```
