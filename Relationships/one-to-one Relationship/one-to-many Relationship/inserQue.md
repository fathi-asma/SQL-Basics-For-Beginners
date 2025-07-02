# 🧾 Database Table information Insert Queries :

## ✨ Insert into Teacher table :

```sql
INSERT INTO Teacher (teacherID, Name)
VALUES (1, 'Amal');
VALUES (2, "Kamal")
```
- `INSERT INTO Teacher (...)`  → Adds data to the teacher table.

- `(teacherID, Name)`  → Columns to insert values into.

- `VALUES (1, 'Amal') ` → Adds ID = 1 and Name = Amal.

- `VALUES (2, 'Kamla') ` → Adds ID = 2 and Name = Kamal.


## ✨ Insert into Student table

```sql
INSERT INTO Passport (StudentID, student_name, teacherID)
VALUES (101, 'Asra', 1);
VALUES (102, 'Akila', 2);
VALUES (103, 'Sara', 2);
vALUES (104, 'Amina', 1),

```

- `INSERT INTO Student (...) ` → Adds data to the student Table.

- `(StudentID, student_name, teacherID)`  → Columns to insert into.

- `VALUES (101, 'Asra', 1);`  → Adds student with ID 101, name 'Asra', and links them to teacher with ID 1.

- `VALUES (102, 'Akila', 2);`  → Adds student with ID 102, name 'Asra', and links them to teacher with ID 2.




