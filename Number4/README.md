- Question 4

```
USE [Assessment]
GO

/*INSERT INTO dbo.EmployeeDetails
           (E_id
           ,firstName
           ,lastName)
     VALUES
           (4,'Allan','Austin')
GO*/

SELECT firstName ,COUNT(*) Repeated FROM dbo.EmployeeDetails GROUP BY firstName HAVING COUNT(*) >1;
```