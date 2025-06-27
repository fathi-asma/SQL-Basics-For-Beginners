# 🧾 Database Table information Insert Queries :

## ✨ Insert into Person table :

```sql
INSERT INTO Person (PersonID, Name)
VALUES (1, 'Asma');
```
- `INSERT INTO Person (...)`  → Adds data to the Person table.

- `(PersonID, Name)`  → Columns to insert values into.

- `VALUES (1, 'Asma') ` → Adds ID = 1 and Name = Asma.

## ✨ Insert into Passport table

```sql
INSERT INTO Passport (PassportID, PersonID, Country)
VALUES (101, 1, 'Sri lanka');
```

- `INSERT INTO Passport (...) ` → Adds data to the Passport table.

- `(PassportID, PersonID, country)`  → Columns to insert into.

- ` VALUES (101, 1, 'Sri lanka')`  → Adds passport with ID 101, links to PersonID 1, and sets country.




