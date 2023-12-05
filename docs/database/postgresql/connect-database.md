---
sidebar_position: 2
---

# Connect to PostgreSQL Database

Running the PostgreSQL interactive terminal program, called psql, which allows you to interactively enter, edit, and execute SQL commands. At the time of installing postgres to your operating system, it creates an "initial DB" and starts the postgres server domain running. Typically initdb creates a table named "postgres" owned by user "current logged in user name"

At the command line in your operating system, type the following command.

## Debian based systems :

```bash
sudo -i -u postgres
```

next type following command.

```bash
psql
```
