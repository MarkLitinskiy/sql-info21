# Info21 v1.0

Data analysis and statistics for School 21.

Project date: 07.2023

## Description

This group project is creating a database of knowledge about School 21 and writing procedures and functions to retrieve the information and procedures and triggers to change it.
I have taken over some of the functions from Part 2 and all of the procedures from Part 4.


#### Database structure:
![model](screenshots/SQL2.png)

### Part 1. Creating the database

Creating the database and all tables.
Procedures are also present to import and export data for each table from/to a .csv file.

### Part 2. Modifying data

1) Write a procedure to add a P2P check;  
2) Write a procedure to add Verter validation;  
3) Write a trigger: after adding a record with the status "start" to the P2P table, change the corresponding record in the TransferredPoints table;  
4) Write a trigger: before adding a record to the XP table, check the correctness of the added record;  

### Part 3. Data retrieval

Procedures and functions to display statistics and information on created tables.

### Part 4. Metadata

Stored procedures for displaying service information on the created database.