# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## Date:

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
create table student(rollno char(5), name varchar(20), age char(5), address varchar(100), phoneno char(15));

### OUTPUT:
![image](https://github.com/kanishka2305/F2_DBMS/assets/113497357/e7e9ba9f-fa55-4e1c-8f87-56e4caf71d30)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
ALTER TABLE student ADD department varchar(30);
### OUTPUT:
![image](https://github.com/kanishka2305/F2_DBMS/assets/113497357/0992143b-4c95-4486-93fb-a8ee654dcadb)


### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![image](https://github.com/kanishka2305/F2_DBMS/assets/113497357/6f103ac8-491e-485a-bfdf-6c5e3e503090)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![image](https://github.com/kanishka2305/F2_DBMS/assets/113497357/53e6d4ae-1918-4cf8-9cbb-e25d0e0c3e7a)



### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/kanishka2305/F2_DBMS/assets/113497357/aefe2b49-f46c-4ff9-9600-37ef2fbb7c78)

## Result:
Hence successfully created a student database and execute DDL queries using SQL.
