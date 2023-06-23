# SQL Notes :floppy_disk:

## Introduction :wave:
SQL (Structured Query Language) is a standard programming language used for managing relational databases. It enables you to store, retrieve, modify, and manipulate data stored in tables.

## Basic SQL Syntax :keyboard:
- SQL statements typically start with a keyword, such as `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
- Tables are the primary way to store data in SQL, identified by a unique name.
- Columns represent specific attributes or data fields within a table.
- Rows contain individual records or data entries in a table.

## SELECT Statement :mag_right:
The `SELECT` statement is used to retrieve data from a database.

Syntax:
```sql
SELECT column1, column2, ...
FROM table_name;
```

Example:
```sql
SELECT * FROM customers;
```

## INSERT Statement :heavy_plus_sign:
The `INSERT` statement is used to insert new records into a table.

Syntax:
```sql
INSERT INTO table_name (column1, column2, ...)
VALUES (value1, value2, ...);
```

Example:
```sql
INSERT INTO customers (name, email) 
VALUES ('John Doe', 'john@example.com');
```

## UPDATE Statement :pencil2:
The `UPDATE` statement is used to modify existing records in a table.

Syntax:
```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```

Example:
```sql
UPDATE customers
SET email = 'newemail@example.com'
WHERE customer_id = 1;
```

## DELETE Statement :x:
The `DELETE` statement is used to remove records from a table.

Syntax:
```sql
DELETE FROM table_name
WHERE condition;
```

Example:
```sql
DELETE FROM customers
WHERE customer_id = 1;
```

---

These are just the basics of SQL. Feel free to explore more advanced concepts and statements. Happy coding! :rocket:
