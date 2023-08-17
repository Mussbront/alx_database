# SQL - Introduction

## Databases

Creating and manipulating databases using <code>MySQL</code>.

## General Learning Objectives

- What’s a database
- What’s a relational database
- What does <code>SQL</code> stand for
- What’s <code>MySQL</code>
- How to create a <code>database</code> in <code>MySQL</code>
- What does <code>DDL</code> and <code>DML</code> stand for
- How to <code>CREATE</code> or <code>ALTER</code> a table
- How to <code>SELECT</code> data from a table
- How to <code>INSERT</code>, <code>UPDATE</code>, or <code>DELETE</code> data
- What are <code>subqueries</code>
- How to use <code>MySQL</code> functions

## General

- Recommended editors: <code>Visual studio code</code>.
- All files will be executed on Ubuntu 20.04 LTS using <code>MySQL 5.7</code> (version 5.7.8-rc).
- All files should end with a new line.
- All SQL queries should have a comment just before (i.e. syntax below).
- All your files should start by a comment describing the task.
- All SQL keywords should be in uppercase (<code>SELECT</code>, <code>WHERE</code>…).
- The length of the files will be tested using <code>wc</code>.

### Comments for SQL File:

<code>$ cat my_script.sql
-- 3 first students in the Batch ID=3
-- because Batch 3 is the best!
SELECT id, name FROM students WHERE batch_id = 3 ORDER BY created_at DESC LIMIT 3;
$</code>