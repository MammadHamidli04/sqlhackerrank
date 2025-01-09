## 1. Weather Observation Station 7
### Query the list of CITY names ending with vowels (a, e, i, o, u) from STATION. Your result cannot contain duplicates.
```sql
SELECT DISTINCT CITY
FROM STATION
WHERE CITY LIKE '%a'
   OR CITY LIKE '%e'
   OR CITY LIKE '%i'
   OR CITY LIKE '%o'
   OR CITY LIKE '%u';
```
## 2. Employee Name
### Write a query that prints a list of employee names (i.e.: the name attribute) from the Employee table in alphabetical order.
```sql
SELECT name
FROM Employee
ORDER BY name ASC;
```
## 3. Employee Salaries
### Write a query that prints a list of employee names (i.e.: the name attribute) for employees in Employee having a salary greater than  per month who have been employees for less than $2000 months. Sort your result by ascending employee_id.
```sql
SELECT name
FROM Employee
WHERE salary > 2000 and months < 10
ORDER BY employee_id ASC;
```