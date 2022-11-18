
- Question 1

```
SELECT Employee.firstname , Employee.lastname Sales.employee_id
FROM Employee WHERE Sales.amount > 0 JOIN  Sales ON  Employee.id = Sales.employee_id
```