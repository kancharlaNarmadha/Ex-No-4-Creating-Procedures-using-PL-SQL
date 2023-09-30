# Ex-No-4-Creating-Procedures-using-PL-SQL
# AIM: 
To create a procedure using PL/SQL.
# Steps:
1.Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);

2.Create a procedure named as insert_employee data.

3.Inside the procdure block, write the query for inserting the values into the employee table.

4.End the procedure.

5.Call the insert_employee data procedure to insert the values into the employee table.

6.Display the employee table

# Program:
```
 create procedure emp_data as
   begin
   insert into employee6(empid,empname,dept,salary)values(1,'Lincy','IOT',90000);
   insert into employee6(empid,empname,dept,salary)values(2,'Dharini','AIML',80000);
   insert into employee6(empid,empname,dept,salary)values(3,'Shabreena','AIDS',70000);
   commit;
   end;
   /

Procedure created.

  begin
  emp_data;
  end;
  /

PL/SQL procedure successfully completed.
```
# Output:
![exp 4](https://github.com/kancharlaNarmadha/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119559316/af12c622-a2af-4602-b8fc-39c5ecace4ea)


# Result:
To create a procedure using PL/SQL was sucessusfully done.
