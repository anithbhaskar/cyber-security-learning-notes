# Day 3 - SQL Basics

## What is SQL?
SQL stands for Structured Query Language. It is used to store, manage, and search data in databases.

## Why SQL is important
SQL is useful in IT, cybersecurity, data analysis, and cloud roles because many systems store information in databases.

## Basic SQL commands

| Command | Meaning |
|---|---|
| `SELECT` | Gets data from a table |
| `FROM` | Chooses which table to use |
| `WHERE` | Filters results |
| `ORDER BY` | Sorts results |
| `INSERT INTO` | Adds new data |
| `UPDATE` | Changes existing data |
| `DELETE` | Removes data |

## Simple example

```sql
SELECT name, email
FROM users
WHERE role = 'admin';
