# 📘 Basic SQL Data Types Guide

Here are some commonly used SQL data types for beginners:

| **Data Type** | **Description**                         | **Example**            |
|---------------|-----------------------------------------|------------------------|
| INT           | Whole numbers                           | 1, 100, -50            |
| FLOAT         | Decimal numbers (approximate)           | 3.14, 9.81             |
| DECIMAL(p,s)  | Decimal with precision and scale        | DECIMAL(5,2) → 99.99   |
| VARCHAR(n)    | Variable-length string (text)           | 'Asma', 'Java'         |
| CHAR(n)       | Fixed-length string                     | 'Y'                    |
| DATE          | Only date                               | '2025-01-01'           |
| DATETIME      | Date and time                           | '2025-01-01 10:30:00'  |
| BOOLEAN       | True/False value (often 1 or 0)         | TRUE, FALSE            |



---



> ## 🧾 Student Table Structure  
> This table stores basic student details.
>
> ### 📋 SQL Code:
> ```
> CREATE TABLE Student (
>     StudentID INT,
>     Name VARCHAR(100),
>     Gender CHAR(1),
>     DateOfBirth DATE,
>     IsActive BOOLEAN
> );
> ```
>
> ### 🧱 Columns Explained with dataTypes :
>
> | Column Name | Data Type | Description |
> |-------------|-----------|-------------|
> | StudentID | `INT` | Unique ID for each student |
> | Name | `VARCHAR(100)` | Full name of the student |
> | Gender | `CHAR(1)` | Gender (e.g., 'M' or 'F') |
> | DateOfBirth | `DATE` | Student's birth date |
> | IsActive | `BOOLEAN` | Status: active (true/false) |

---

