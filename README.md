# DataBase Keys

**By**: Nishchal Mishra, Maneel Reddy, Yu Hsin Wang, Alex Bradshaw.

This repository contains our group presentation for our MSDS 610: Communication for Analytics course, where we are presenting our views on the importance of DataBase Keys.

## Goal 
For this presentation we wanted to highlight the importance of DataBase Keys and showcase how we can implement 4 most important types of keys and comstraints they have upon them which will help us to have a better understanding of our data.


## Procedure Summary

We will create a database with 2 tables, "STUDENT" and "COURSES".</br>
The table “STUDENT” consists of student information. </br>
while the table “STUD_COURSE” consists of the courses that a student is enrolled in.</br>

## <br><b>1. Unique Key</b></br>
1. In RDMS, a unique key is a key that enforces uniqueness(every data point in the column is unique). 
2. A unique key can take NULL values
3. It is not the primary key. 


## <br><b>2. Primary Key</b></br>
1. A primary key is a key that can uniquely identify every record in the table.</br>
2. A primary key has to be unique and not null</br>



## <br><b>3. Foreign Key</b></br>
A foreign key is a key that refers to the primary key in another table. 
1. The foreign key links both tables and enforces referential integrity. 
2. This referential integrity ensures that for every foreign key, there is a corresponding table with the same attribute as a primary key. 
3. If a column is assigned a foreign key, each row of that column must contain a value that exists in the ‘foreign’ column it references.


## <br><b>4. Composite Key</b></br>
1. A composite key is made by the combination of two or more columns in a table that can be used to uniquely identify each row in the table.
2. When the columns are combined uniqueness of a row is guaranteed, but when it is taken individually it does not guarantee uniqueness.
3. It can also be understood as a primary key made by the combination of two or more attributes to uniquely identify every row in a table.


## Conclusion
DataBase Keys are fundamental tool to create and manage a database management system, strong understanding and assignment of keys are detrimental to traverse the DBMS smoothly.
