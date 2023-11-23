```sql
SELECT Employees.employee_name, Salaries.salary
FROM Employees
LEFT JOIN Salaries ON Employees.employee_id = Salaries.employee_id;
```
