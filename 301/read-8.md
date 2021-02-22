# SQL

SQL (pronounced "ess-que-el") stands for Structured Query Language. SQL is used to communicate with a database.

SQL statements are used to perform tasks such as update data on a database, or retrieve data from a database.

Some common relational database management systems that use SQL are: Oracle, Sybase, Microsoft SQL Server, Access, Ingres, etc.

The standard SQL commands such as "Select", "Insert", "Update", "Delete", "Create", and "Drop" can be used to accomplish almost everything that one needs to do with a database.(1)

## Table Basics

A relational database system contains one or more objects called tables.

The data or information for the database are stored in these tables.

Tables are uniquely identified by their names and are comprised of columns and rows.

Columns contain the column name, data type, and any other attributes for the column.

Rows contain the records or data for the columns.(1)

## Selecting Data

The select statement is used to query the database and retrieve selected data that match the criteria that you specify.

```select "column1"```

  ```[,"column2",etc]``` 

  ```from "tablename"```

  ```[where "condition"];```
  
  ```[] = optional```

## Creating Tables

The create table statement is used to create a new table

```create table "tablename"```

```("column1" "data type",```

 ```"column2" "data type",```

 ```"column3" "data type");```

# references

1. http://www.sqlcourse.com/table.html