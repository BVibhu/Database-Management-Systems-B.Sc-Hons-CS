# Database Management Systems

## Practical:

Create and use the following database schema to answer the given queries.

**EMPLOYEE Schema**

| **Field** | **Type** | **DEFAUL NULL KEY**** T** |
| --- | --- | --- |
| Eno | Char(3) | NO PRI NIL |
| Ename | Varchar(50) | NO NIL |
| Job\_type | Varchar(50) | NO NIL |
| Manager | Char(3) | Yes FK NIL |
| Hire\_date | Date | NO NIL |
| Dno | Integer | YES FK NIL |
| Commission | Decimal(10,2) | YES NIL |
| Salary | Decimal(7,2) | NO NIL |
| **DEPARTMENT Schema** |

**DEFAUL**

**Field**** Type ****NULL KEY**** T**

| Dno | Integer | No PRI | NULL |
| --- | --- | --- | --- |
| Dname | Varchar(50) | Yes | NULL |
| Location | Varchar(50) | Yes | New Delhi |

**Query List**

1. Query to display Employee Name, Job, Hire Date, Employee Number; for each employee with the Employee Number appearing first.

1. Query to display unique Jobs from the Employee Table.

1. Query to display the Employee Name concatenated by a Job separated by a comma.

1. Query to display all the data from the Employee Table. Separate each Column by a comma and name the said column as THE\_OUTPUT.

1. Query to display the Employee Name and Salary of all the employees earning more than $2850.

1. Query to display Employee Name and Department Number for the Employee No= 7900.

1. Query to display Employee Name and Salary for all employees whose salary is not in the range of $1500 and $2850.

1. Query to display Employee Name and Department No. of all the employees in Dept 10 and Dept 30 in the alphabetical order by name.

1. Query to display Name and Hire Date of every Employee who was hired in 1981.

1. Query to display Name and Job of all employees who don't have a current Manager.

1. Query to display the Name, Salary and Commission for all the employees who earn commission.

1. Sort the data in descending order of Salary and Commission.

1. Query to display Name of all the employees where the third letter of their name is 'A'.

1. Query to display Name of all employees either have two 'R's or have two 'A's in their name and are either in Dept No = 30 or their Manger's Employee No = 7788.

1. Query to display Name, Salary and Commission for all employees whose Commission Amount is 14 greater than their Salary increased by 5%.

1. Query to display the Current Date.

1. Query to display Name, Hire Date and Salary Review Date which is the 1st Monday after six months of employment.

1. Query to display Name and calculate the number of months between today and the date each employee was hired.

1. Query to display the following for each employee \<E-Name\> earns \< Salary\> monthly but wants \< 3 \* Current Salary \>. Label the Column as Dream Salary.

1. Query to display Name with the 1st letter capitalized and all other letter lower case and length of their name of all the employees whose name starts with 'J', 'A' and 'M'.

1. Query to display Name, Hire Date and Day of the week on which the employee started.

1. Query to display Name, Department Name and Department No for all the employees.

1. Query to display Unique Listing of all Jobs that are in Department # 30.

1. Query to display Name, Dept Name of all employees who have an 'A' in their name.
2. Query to display Name, Job, Department No. And Department Name for all the employees working at the Dallas location.

1. Query to display Name and Employee no. Along with their Manger's Name and the Manager's employee no; along with the Employees' Name who do not have a Manager.

1. Query to display Name, Dept No. And Salary of any employee whose department No. and salary matches both the department no. And the salary of any employee who earns a commission.

1. Query to display Name and Salaries represented by asterisks, where each asterisk (\*) signifies $100.

1. Query to display the Highest, Lowest, Sum and Average Salaries of all the employees

1. Query to display the number of employees performing the same Job type functions.

1. Query to display the no. of managers without listing their names.

1. Query to display the Department Name, Location Name, No. of Employees and the average salary for all employees in that department.

1. Query to display Name and Hire Date for all employees in the same dept. as Blake.

1. Query to display the Employee No. And Name for all employees who earn more than the average salary.
2. Query to display Employee Number and Name for all employees who work in a department with any employee whose name contains a 'T'.

1. Query to display the names and salaries of all employees who report to King.

1. Query to display the department no, name and job for all employees in the Sales department.



# Theory: 

**1.Introduction** 

Characteristics of database approach, data models, database system architectureand data independence.

**2.Entity Relationship(ER) Modeling** 

Entity types, relationships, constraints.

**3.Relation data model** 

Relational model concepts, relational constraints, relational algebra, SQLqueries

**4.Database design** 

Mapping ER/EER model to relational database, functional dependencies,Lossless decomposition, Normalforms(upto BCNF).

**5.Transaction Processing** 

ACID properties, concurrency control

**6.File Structure and Indexing** 

Operations on files, File of Unordered and ordered records, overview of File organizations,

Indexing structures for files( Primary index, secondary index, clustering index), Multilevel indexing using B and B+ trees.

**Books Recommended:**

1. R. Elmasri, S.B. Navathe, Fundamentals of Database Systems 6th Edition, Pearson Education, 2010.

1. R. Ramakrishanan, J. Gehrke, Database Management Systems 3rd Edition, McGraw-Hill, 2002.

1. A. Silberschatz, H.F. Korth, S. Sudarshan, Database System Concepts 6th Edition, McGraw Hill, 2010.

1. R. Elmasri, S.B. Navathe Database Systems Models, Languages, Design and application Programming, 6th Edition, Pearson Education,2013.


