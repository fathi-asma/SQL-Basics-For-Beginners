# 🧾 Database Table creation Queries :

## Person Table : 

```sql
CREATE TABLE Person
(
    PersonID INT PRIMARY KEY,
    Name VARCHAR(100)
);
```

-  `CREATE TABLE  Person (`  → Start creating the table.

- `PersonID INT PRIMARY KEY` , → ID column, must be unique.

- `Name VARCHAR(100)`  → Person’s name, max 100 characters.

- `);`  → Ends the table creation.

----

## Passport Table : 

```sql
CREATE TABLE Passport
(
    PassportID INT PRIMARY KEY,
    PersonID INT UNIQUE,
    PassportNumber VARCHAR(50),
    FOREIGN KEY (PersonID) REFERENCES Person(PersonID)
);
```
- `CREATE TABLE  Passport ( ` - Start creating a table named Passport.

- `PassportID INT PRIMARY KEY,` - Add a column called PassportID. It's a number (INT) and the main ID (Primary Key) for this table.

- `PersonID INT UNIQUE,` - Add a column called PersonID. It's a number and must be unique (only one per person). It links to the Person table.

- `PassportNumber VARCHAR(50),` - Add a column to store the passport number (text, max 50 characters).

- `FOREIGN KEY (PersonID) REFERENCES Person(PersonID)` - This line links PersonID to the Person table's PersonID. It makes sure each passport belongs to a valid person.

- `);` - close the table creations. 









