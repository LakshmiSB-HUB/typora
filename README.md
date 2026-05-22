# Student overview

The Student table is the core of the database, designed to store and manage student information. It ensures data integrity through unique identifiers, validation rules, and constraints.

## The description of student database is as follows :

- [x] **Student_ID :** `integer, primary key`
- [x] **Student_No :** `10-character string, required unique`
- [x] **Full_Name :** `Upto 100 characters required`
- [x] **Email :** `upto 150 characters required ,unique`
- [x] **GPA :** `decimal must be between 0.00 and 4.00`
- [x] **Status :** `must be one of the following Active, Inactive and Graduated`
- [x] **Enrolled_at :** `datetime, defaults to current timestamp`


## Functionality

- Maintains unique student records.

- Tracks academic performance via GPA.

- Monitors student lifecycle (active, inactive, graduated).

- Provides audit trail with enrollment timestamps.





