# Student List

## Create a new database
Create a new database for this exercise.
```
CREATE DATABASE exercise_student_list
use exercise_student_list
``

## Create the student table
Create a table named **students** with the following columns:  
```
id (integer, primary key)  
name (varchar, maximum length 50)  
age (integer)  
grade (float)  
```

> ANSWER  

## Insert and Modify Data
### 1. Insert Data
Insert these records into the students table with the following data:
```
(1, 'John Doe', 20, 85.5, '123 Main St')
(2, 'Jane Smith', 22, 92.0, '456 Oak Ave')
(3, 'Bob Johnson', 21, 78.5, '789 Pine Rd')
(4, 'Tina Turner', 25, 71.0, '45 Columbia St')
```

> ANSWER  

### Update Data
Update the grade of 'Jane Smith' to 95.0.

> ANSWER  

### Delete Data
Delete the record of the student with id 3 from the students table.

> ANSWER  

### Select Data
Write a query to retrieve the names and ages of all students.  

> ANSWER  

### Bonus: Select the best students
Write a query to retrieve the names and grade of all students with a grade higher than 80.

> ANSWER  
CREATE DATABASE exercise;
use exercise;
CREATE TABLE Students(id INT, name VARCHAR(50), age INT, grade INT, PR
INSERT INTO Students(id,name,age,grade) VALUES(2,'Pit',25,10);IMARY KEY(id));
ALTER TABLE Students ADD adress VARCHAR(50);
UPDATE Students SET adress='Odesa' WHERE id=2;
UPDATE Students SET age='21' WHERE name='Pit';
DELETE FROM Students WHERE id=1;
select name,age FROM Students;
SELECT name, grade FROM Students WHERE grade>9;
INSERT INTO Students(id,name,age,grade) VALUES(1,'John',20,85);
SELECT name, grade FROM Students WHERE grade>9;

INSERT INTO Students(id,name,age,grade) VALUES(1,'John',20,85);

