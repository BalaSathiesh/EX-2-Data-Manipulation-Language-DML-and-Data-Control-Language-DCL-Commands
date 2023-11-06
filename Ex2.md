# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## Date : 11/8/23
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```

## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/9bcc2a95-5dfd-4a98-9ec7-66a41d6f1f4f)





### OUTPUT:

![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/aa5d800d-2030-44c5-908b-d8af8fbaabca)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/f7d52279-67e8-4009-9d17-c096b1dae578)



### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/141e7e81-aa89-4f5b-ab2c-1c6ec7ee4242)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/5e19d80f-abe6-4a0d-aa00-96f945ee6d8f)



### OUTPUT:

![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/a2ab0c40-451e-4549-97fb-6ac9fc099cd5)


### Q4)	List the names of Clerks from emp table.


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/e544ceb3-fcbc-48e1-bbb4-bbe794d5c3fb)



### OUTPUT:

![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/538fd06a-2c14-4bef-88da-4b98bfb831b4)



### Q5)	List the names of employee who are not Managers.


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/eb6297ef-4380-470b-b202-11e2db60a9ce)


### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/9de026bb-8b92-466a-b7c8-018bb724d07b)


### Q6)	List the names of employees not eligible for commission.


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/541ba287-af71-4e04-993d-fbc0add083dd)

### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/97e73a6f-bf0b-4e33-a95d-758230c08f8a)


### Q7)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/0e6ba077-c301-4120-b2e9-cf2699c57a9f)




### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/953813ca-4d40-4d7f-9b72-a0fda3ab4f90)


### Q8) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/23b85ef8-d854-4451-9625-e1fbe427789f)



### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/e8832e38-bb8d-4991-832f-6e299717dc9e)




### Q9) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/ffa41583-3e13-429f-9209-2047d89487f2)



### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/232b6460-23b0-485a-8049-01e728647b94)



### Q10)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/0adc90d8-66e4-48fb-91b7-81d8cf46b708)




### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/2d57eeef-81fe-47e2-9626-07c9f1d7ad41)



### Q11) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:

![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/d7488ff4-b055-48b1-9613-5dc0b5c1f3ff)


### OUTPUT:

![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/d0693a52-f438-4bcb-9c7b-2ba274b0ceef)



### Q12) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/71ccba87-614c-448d-bcdd-c2e55d9a036f)




### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/f5eef05f-24c5-4a61-87ac-eeddb7b64092)



### Q13) Find maximum, minimum and average salary in EMP table.

### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/95c06d43-90f7-4955-af13-9854e5430832)



### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/d7de52e5-6dac-4400-a2ee-505779b88215)



### Q14) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/eab920a7-d6b2-4bf0-8bde-211eb88d9829)


### OUTPUT:
![image](https://github.com/BalaSathiesh/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/128462891/96e1d703-7bca-4ad0-b385-8e8ad5c95482)



### RESULT:
QUERIES EXECUTED SUCCESSFULLY.
