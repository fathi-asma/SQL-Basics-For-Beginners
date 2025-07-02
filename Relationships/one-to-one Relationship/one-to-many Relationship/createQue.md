# 🧾 Database Table creation Queries :

## Teacher Table : 

```sql
CREATE TABLE Teacher
(
    teacherID INT PRIMARY KEY,
    Name VARCHAR(100)
);
```

-  `CREATE TABLE  Teacher (`  → Start creating the table.

- `teacherID INT PRIMARY KEY` , → ID column, must be unique.

- `Name VARCHAR(100)`  → Person’s name, max 100 characters.

- `);`  → Ends the table creation.

----

## Student Table : 

```sql
CREATE TABLE Student
(
    studentID INT PRIMARY KEY,
    teacherID INT,
    student_name VARCHAR(50),
    FOREIGN KEY (teacherID) REFERENCES Person(TeacherID)
);
```
- `CREATE TABLE  Student ( ` - Start creating a table named Student.

- `studentID INT PRIMARY KEY,` - Add a column called studentID. It's a number (INT) and this means it uniquely identifies each student.

- `teacherID INT,` - Add a column called teacherID. This is used to show which teacher is assigned to the student.

- `FOREIGN KEY (teacherID) REFERENCES Person(TeacherID)` - The value in `teacherID` must match a `TeacherID` in the Teacher table.This connects the Student table to the Teacher table. It creates a foreign key, which forms a one-to-many relationship

- `);` - close the table creations. 









