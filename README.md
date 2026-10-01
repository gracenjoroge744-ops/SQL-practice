# SQL-practice

My hands-on SQL practice using MySQL and MySQL Workbench. I'm learning SQL to work with data in public health and data science.

## Projects

### Company database (Complex_database.sql) - in progress

A database for a paper company, built from scratch. It currently includes:

- *employee*: staff details, with a supervisor link back to the same table
- *branch*: company branches, each with a manager
- *client*: clients, each linked to a branch
- *works_with*: which employees work with which clients, and their total sales
- *branch_supplier*: suppliers for each branch

## What I've practiced

- Creating databases and tables
- Primary keys, including composite primary keys (works_with)
- Foreign keys linking tables together
- ON DELETE CASCADE and ON DELETE SET NULL
- Adding data with INSERT INTO
- Changing existing rows with UPDATE ... SET ... WHERE
- Reading and fixing common errors (missing commas, wrong column counts, table name typos)

## Next steps

- Finish inserting data into all the tables
- SELECT with WHERE, ORDER BY, and LIMIT
- Joins across tables
- Aggregate functions (COUNT, AVG, GROUP BY)

## Tools

MySQL Server (Community Edition) and MySQL Workbench.

## Note

All data is made-up practice data. No real or personal information is included.
