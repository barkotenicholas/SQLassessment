-  number 3


```
USE Assessment

GO

CREATE PROCEDURE AddEmployee
	@id int,
	@firstName nvarchar(50),
	@lastName  nvarchar(50)
AS
	SET NOCOUNT ON
	INSERT INTO Employee (id,first_name,last_name) VALUES (@id,@firstName,@lastName)
GO

EXEC AddEmployee @id=54 ,@firstName ='Elvis',@lastName ='Atis'

GO
```