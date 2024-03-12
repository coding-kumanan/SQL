# SQL

## Fundamentals

## What is data?
Data is a collection of values. Those values can be charectors, numbers, or any other data types. 

## What is information?
Information is a collection of data. Information is a data that was processed in a way that human can understand,read and use it. 

## Example of Data is 
```
kumanan,123, main street, manivannan, 630550

In above example the data is random words and numbers sperated by commas. 

```
## Example of information is 

```
Manivannan kumanan
123 main street
630557 

In above example the information is oraganized and formated using data.
this is contact information of manivannan kumanan
```

## What is database ?
Database is a organized collection of data typically stored electronically in a computer system . It is usually controlled by th Database management system. 

## What is Database Mangement System?
Database Mangement system also refered as DBMS It is a software to manage databases. It act like inferface between database and its end users or Programs. DBMS allows users to retrive, update, insert and delete data from the Database. It also do variety of admistrative operation like user management, backup, monitor and recovery in the database.

## What are the different types of data models in DBMS are
```
1. hierarchical DB model 
2. Network DB model 
3. Relational DB model 

```

## What is Relational DB MODEL 
Developed by E.F. Codd from IBM in the 1970s, he proposed data can be stored in the form of tables. The relational database model allows any table to be related to another table using a common attribute. 
Table is logical structure consist of Row and Colums. Row is also called Records or Tuples. Colums also called artibutes or fields.

Attributes (columns) specify a data type, and each record (or row) contains the value of that specific data type. All tables in a relational database have an attribute known as the primary key, which is a unique identifier of a row, and each row can be used to create a relationship between different tables using a foreign key—a reference to a primary key of another existing table. 

## SQL Defenition (Structured Query Language):
SQL was invented in the 1970s based on the relational data model by Donald Chamberlin and Raymond Boyce. It was initially known as the structured English query language (SEQUEL). The term was later shortened to SQL.

It is a high level programming language used to storing, and processing information in a relational database. we can use SQL statement to store, remove, update, search, retrive information from the database. SQL also used to maintain and optimize database performance. 

All queries in a SQL are ended with semicolon. It is not case sensitive. 

## Data Integrity:
Data Integrity is used to maintain the accuracy and consistency of data in a table. It is used to restric the invalid or duplicate data entered into the  table. 

we can achive data intergrity in two ways 
```
    1. Data Types
    2. Constrains 
```
## Data Types:
A data type is an attribute that specifies the type of data that the object can hold. It is used to specify the types of data to be stored for the selected column in the table. The different types of Data Types are in Orcale SQL
```
Numbers, Character, Varchar2, Date.

```
## Number DataType: 
It is an attribute that specifies the numeric values of data. This will allow only numbers to store. 

Syntax:
```
NUMBER (SIZE) 
CREATE TABLE persons (persion_id NUMBER(3));
```





