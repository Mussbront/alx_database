# SQL Introduction

## 0. List Databases

Script that lists all the databases in a MySQL server.

## 1. Create Database

Script that creates the database <code>hbtn_0c_0</code> in the MySQL server.
- The script should not fail if the <code>hbtn_0c_0</code> database already exists.
- <code>SELECT</code> and <code>SHOW</code> statements should not be used.


## 2. Remove Database

Script that deletes the database <code>hbtn_0c_0</code> in the MySQL server.
- The script should not fail if the <code>hbtn_0c_0</code> database does not exists.
- <code>SELECT</code> and <code>SHOW</code> statements should not be used.

## 3. List Tables

Script that lists all the tables of a database in the MySQL server.
- The database name will be passed as argument of <code>mysql</code> command.

## 4. First Table

Script that creates a table called <code>first_table</code> in the current database in the MySQL server.

- <code>first_table</code> description:
    - <code>id</code> INT
    - <code>name</code> VARCHAR(256)

- The database name will be passed as an argument of the <code>mysql</code> command.
- If the table <code>first_table</code> already exists, the script should not fail.
- <code>SELECT</code> or <code>SHOW</code> statements should not be used.

## 5. Full Table

Script that prints the full description of the table <code>first_table</code> from the database <code>hbtn_0c_0</code> in the MySQL server.

- The database name will be passed as an argument of the <code>mysql</code> command.
- <code>DESCRIBE</code> or <code>EXPLAIN</code> statements should not be used.

## 6. List Values

Script that lists all rows of the table <code>first_table</code> from the database <code>hbtn_0c_0</code> in the MySQL server.

- All fields should be printed.
- The database name will be passed as an argument of the <code>mysql</code> command.

## 7. Insert Value

Script that inserts a new row in the table <code>first_table</code> (database <code>hbtn_0c_0</code>) in the MySQL server.

- New row:
    - <code>id</code> = <code>89</code>
    - <code>name</code> = <code>Holberton School</code>
- The database name will be passed as an argument of the <code>mysql</code> command.

## 8. Count 89

Script that displays the number of records with <code>id = 89</code> in the table <code>first_table</code> of the database <code>hbtn_0c_0</code> in the MySQL server.

- The database name will be passed as an argument of the <code>mysql</code> command.

## 9. Full Creation

Script that creates a table <code>second_table</code> in the database <code>hbtn_0c_0</code> in the MySQL server and add multiples rows.

- <code>second_table</code> description:
    - <code>id</code> INT
    - <code>name</code> VARCHAR(256)
    - <code>score</code> INT
- The database name will be passed as an argument to the <code>mysql</code> command.
- If the table <code>second_table</code> already exists, the script should not fail.
- <code>SELECT</code> and <code>SHOW</code> statements should not be used.
- The script should create these records:
    - <code>id</code> = 1, <code>name</code> = “John”, <code>score</code> = 10
    - <code>id</code> = 2, <code>name</code> = “Alex”, <code>score</code> = 3
    - <code>id</code> = 3, <code>name</code> = “Bob”, <code>score</code> = 14
    - <code>id</code> = 4, <code>name</code> = “George”, <code>score</code> = 8