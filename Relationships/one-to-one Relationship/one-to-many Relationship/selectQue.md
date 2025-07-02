# 🧾 Database Table information Select Queries :

``` sql 
SELECT * FROM Student;
```
- This shows all the data from the`Student`table.



----

## To show student table with teacher names

``` sql
SELECT Student.StudentID, Student.Name AS StudentName, Teacher.Name AS TeacherName
FROM Student
JOIN Teacher ON Student.TeacherID = Teacher.TeacherID;
```


# 🧾 Database Table information update Queries :

``` sql 
UPDATE Student
SET Name = 'Amina', TeacherID = 2
WHERE StudentID = 101;

```
- `UPDATE Passport `– Modifies the student table

- `SET Name` = 'Amina', TeacherID = 2
`WHERE StudentID` = 101 -  This updates the student with ID `101` to have the name `Amina` and assigns `TeacherID 2`.

----

# 🧾 Database Table information delete Queries :

``` sql 
DELETE FROM Student
WHERE StudentID = 101;

```
-  This removes the student with ID 101.

