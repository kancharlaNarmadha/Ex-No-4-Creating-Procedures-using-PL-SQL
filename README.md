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
Enter user-name: system
Enter password:
Last Successful login time: Wed Sep 27 2023 13:17:52 +05:30

Connected to:
Oracle Database 21c Express Edition Release 21.0.0.0.0 - Production
Version 21.3.0.0.0

SQL> create table employees(empid int,empname varchar(12),dept varchar(10),salary int);

Table created.

SQL> create procedure insert_employees_data as begin
  2  insert into employees(empid,empname,dept,salary)values(1,'Lincy','IOT',80000);
  3  insert into employees(empid,empname,dept,salary)values(2,'Dharini','AIML',90000);
  4  insert into employees(empid,empname,dept,salary)values(3,'Shareena','AIDS',60000);
  5  commit;
  6  end;
  7  /

Procedure created.
```
# Output:
![DBMS EXP 4](https://github.com/kancharlaNarmadha/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119559316/31c3834e-36c2-4370-bc27-938f4bc4cc21)
# Result:
To create a procedure using PL/SQL was sucessusfully done.
