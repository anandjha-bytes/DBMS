### EXP1 – Basic DDL, DML, and Simple Queries

- **Q1. Create Employee_master from EMPLOYEE**

  ```sql
  CREATE TABLE Employee_master AS
  SELECT * FROM EMPLOYEE;
 - ** Q2. Display all records from Employee_master

```SQL
SELECT * FROM Employee_master;
 - ** Q3. Delete all employees of department 10 from Employee_master

SQL
DELETE FROM Employee_master
WHERE DEPTNO = 10;

