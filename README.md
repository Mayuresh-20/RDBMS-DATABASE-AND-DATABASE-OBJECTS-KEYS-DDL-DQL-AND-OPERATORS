# RDBMS-DATABASE-AND-DATABASE-OBJECTS-KEYS-DDL-DQL-AND-OPERATORS

► What is RDBMS?

RDBMS stands for Relational Database Management System. RDBMS is the basis for SQL, and for all modern database systems like MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access. A Relational database management system (RDBMS) is a database management system (DBMS) that is based on the relational model as introduced by E. F. Codd.

► What is a table?

The data in an RDBMS is stored in database objects which are called as tables. This table is basically a collection of related data entries and it consists of numerous columns and rows.

Remember, a table is the most common and simplest form of data storage in a relational database. The following program is an example of a CUSTOMERS table −

![image](https://user-images.githubusercontent.com/91977965/137262193-9f64e997-ad15-4a50-ab2c-6678a0a14676.png)


► What is a field?

Every table is broken up into smaller entities called fields. The fields in the CUSTOMERS table consist of ID, NAME, AGE, ADDRESS and SALARY.

A field is a column in a table that is designed to maintain specific information about every record in the table.

► What is a Record or a Row?

A record is also called as a row of data is each individual entry that exists in a table. For example, there are 7 records in the above CUSTOMERS table. Following is a single row of data or record in the CUSTOMERS table −

![image](https://user-images.githubusercontent.com/91977965/137262232-4cab3b37-adf6-4cd1-9337-9fa7288d8d61.png)


A record is a horizontal entity in a table.

► What is a column?

A column is a vertical entity in a table that contains all information associated with a specific field in a table.

For example, a column in the CUSTOMERS table is ADDRESS, which represents location description and would be as shown below −

![image](https://user-images.githubusercontent.com/91977965/137262259-8a14133f-e8d8-4089-b2e1-a68687677e9f.png)


► What are the 6 main objects of a database?


Databases in Access are composed of four objects: What are the six database objects? 

1. Tables. Tables are responsible for storing information within the database. 

2. Relationships. 

3. Queries. 

4. Forms. 

5. Reports. 

6. Macros. 

Together, these objects allow you to enter, store, analyze, and compile your data however you want.


• Various Syntax in SQL

► SQL CREATE INDEX Statement

CREATE UNIQUE INDEX index_name

ON table_name ( column1, column2,...columnN);


► SQL DROP INDEX Statement

ALTER TABLE table_name

DROP INDEX index_name;


► SQL CREATE TABLE Statement

CREATE TABLE table_name(

column1 datatype,

column2 datatype,

column3 datatype,

.....

columnN datatype,

PRIMARY KEY( one or more columns )

);


► SQL SELECT Statement

SELECT column1, column2....columnN

FROM   table_name;


► SQL ALTER TABLE Statement

ALTER TABLE table_name {ADD|DROP|MODIFY} column_name {data_ype};


► SQL ALTER TABLE Statement (Rename)

ALTER TABLE table_name RENAME TO new_table_name;


► SQL INSERT INTO Statement

INSERT INTO table_name( column1, column2....columnN)

VALUES ( value1, value2....valueN);


► SQL UPDATE Statement

UPDATE table_name

SET column1 = value1, column2 = value2....columnN=valueN

[ WHERE  CONDITION ];


► SQL DELETE Statement

DELETE FROM table_name

WHERE  {CONDITION};

► SQL CREATE DATABASE Statement

CREATE DATABASE database_name;


► SQL DROP DATABASE Statement

DROP DATABASE database_name;



► Structured Query Language(SQL) as we all know is the database language by the use of which we can perform certain operations on the existing database and also we can use this language to create a database. SQL uses certain commands like Create, Drop, Insert, etc. to carry out the required tasks. 

1. DDL – Data Definition Language

2. DQl – Data Query Language


► DDL (Data Definition Language): 

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. List of DDL commands: 

• CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).

• DROP: This command is used to delete objects from the database.

• ALTER: This is used to alter the structure of the database.

• TRUNCATE: This is used to remove all records from a table,including all spaces allocated for the records are removed.

• COMMENT: This is used to add comments to the data dictionary.

• RENAME: This is used to rename an object existing in the database.

► DDL (Data Definition Language): 

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.

List of DDL commands: • 

• CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).

• DROP: This command is used to delete objects from the database.

• ALTER: This is used to alter the structure of the database.

• TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.

• COMMENT: This is used to add comments to the data dictionary.

• RENAME: This is used to rename an object existing in the database.


► What is an Operator in SQL?

An operator is a reserved word or a character used primarily in an SQL statement's WHERE clause to perform operation(s), such as comparisons and arithmetic operations. These Operators are used to specify conditions in an SQL statement and to serve as conjunctions for multiple conditions in a statement.

• Arithmetic operators

• Comparison operators

• Logical operators

• Operators used to negate conditions

► SQL Arithmetic Operators
Assume 'variable a' holds 10 and 'variable b' holds 20, then −

![image](https://user-images.githubusercontent.com/91977965/137263132-dc3f2e70-8d6e-49d9-9132-67556f051a6e.png)


SQL Comparison Operators
Assume 'variable a' holds 10 and 'variable b' holds 20, then −

![image](https://user-images.githubusercontent.com/91977965/137263193-10397fc4-b127-471c-86b0-bb708bf1f7a0.png)

SQL Logical Operators

![image](https://user-images.githubusercontent.com/91977965/137263517-c607a3a9-7848-4f89-b249-64338ef240da.png)

![image](https://user-images.githubusercontent.com/91977965/137263589-0fe1884b-6253-4d3a-a3ba-b8e8cde22a58.png)



