# Task 3: Writing Basic SELECT Queries

## 🎯 Objective
To extract data from one or more tables using SQL `SELECT` statements and practice filtering, sorting, and limiting results.
 Tools Used

- MySQL Workbench

 Concepts Practiced
- Retrieving all columns using `SELECT *`
- Selecting specific columns
- Filtering records using:
  - `WHERE`
- Sorting using `ORDER BY`
- Limiting results using `LIMIT`

Example Queries

1. Select all columns from the employees table
 Select * from  members;

-- 2. Select specific columns
SELECT name FROM members;

-- 3. Filter using WHERE 
  select *from members where Member_id=121;

-- 4. Sort results by salary
  select name  from members order by Member_id;

-- 5. Limit output to top 2 rows
 select * from members  order by Member_id limit 3;

