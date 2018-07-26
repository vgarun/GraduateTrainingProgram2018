
ProblemSet 01
==============

BookReference : This assignment is based on the exercises in Connolly and Begg text book at the end of Chapter 13, pp. 437-439.

What to Hand In:
---------------

For each table, you must show the SQL CREATE TABLE statement and any ALTER TABLE statements you use to set up your tables along with the results of those statements. You must also hand in a DESCRIBE statement for each one of the tables you create that shows a list of the columns in the table and their datatypes and lengths.

The best way to capture this information (the CREATE, ALTER, and DESCRIBE statements and their results) is to copy and paste your SQL commands and their results to a Notepad file. When you are done with all the parts of the assignment, you can print out the Notepad file and hand it in. As an example of what to hand in for the CREATE TABLE portion of the assignment, let’s say you create the TEST3 table. The primary key is a NUMBER with a maximum length of 6. The primary key column name is TEST3COL1. The table has two other columns: TEST3COL2 which is a VARCHAR2 of length 20 and TEST3COL3 which is a DATE.

Here is what you would hand in for the creation of this table. It includes a copy of your SQL CREATE TABLE statement, the SQL result saying that the table has been created, your execution of the DESC statement, and its result showing the definition of all the columns in that table.

```sql

SQL> create table test3

        (test3col1 number (6),

         test3col2 varchar2 (20),

         test3col3 date,

         constraint pk_test3

         primary key (test3col1));

Table created.

```


```sql

SQL> desc test3

 Name                            Null?    Type

 ------------------------------- -------- ----

 TEST3COL1                       NOT NULL NUMBER(6)

 TEST3COL2                                VARCHAR2(20)

 TEST3COL3                                DATE

```
You will use the data in the DATA section of this assignment to populate the database, i.e., use INSERT and UPDATE statements to insert the rows of values into the tables. You do not need to hand in copies or feedback from any of your INSERT and UPDATE statements. Once you have inserted all the data into your tables, you will create SELECT statements that will provide answers to the questions listed in the QUESTIONS section of this assignment. For each question, please hand in a copy of the SELECT statement you issue and the SQL Plus feedback. Again, the best way to do this is to copy and paste to a Notepad file. You can include this information in the same Notepad file you use to show your TABLE CREATE statements.

As an example of what to hand in for this portion of the assignment, let’s use the TEST3 table. Suppose it contains the following data:

```sql

TEST3COL1 TEST3COL2            TEST3COL3

--------- -------------------- ---------

   556677 Bicycle Seat         02-JAN-97

   443322 Air Pump             14-JAN-97

   889977 Water Bottle         27-JAN-97

```

If the question is “List all the data in table TEST3,” here is what you would show in your Notepad file. It includes a copy of the question (it’s important that you identify the question your SELECT statement is attempting to answer), your SELECT statement and the results of that SELECT statement. List all the data in table TEST3.

```sql


SQL> select * from test3;

TEST3COL1 TEST3COL2            TEST3COL3

--------- -------------------- ---------

   556677 Bicycle Seat         02-JAN-97

   443322 Air Pump             14-JAN-97

   889977 Water Bottle         27-JAN-97
   
```

Table Descriptions
-------------------

The following set of tables make up a database that is used by a booking agency to book hotel reservations for their client hotels. Attributes that are underscored make up the primary key for that table. Attributes marked with @ denote a foreign key which refers to the primary key of another of the tables. In the Room table, Hotel_No is a foreign key which refers to the primary key of the Hotel table. Type of room is a one-character code that refers to smoking (S) or non-smoking (N). Price refers to the price of the room per night.

In the Booking table, Guest_No refers to the primary key of the Guest table; Hotel_No and Room_No combined refer to the primary key of the Room table.

```
Hotel              (Hotel_No, Name, City)
Room               (Room_No, @Hotel_No, Type, Price)
Booking            (@Hotel_No, @Guest_No, Date_From, Date_To, @Room_No)
Guest              (Guest­_No, Name, City)
```

For every table, it is up to you to decide which is the appropriate datatype for each one of the columns based on the column descriptions given above. If you make assumptions that affect the way you define the columns, please note those assumptions in your assignment.
