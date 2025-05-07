# SQLite Zero To Hero

SQLite Zero To Hero using www.sqlitetutorial.net

## Quiz

### *(answers are in tutorial)*

### SQLite Sample Database

1. open db
1. exit

### SQLite Commands

1. add a database to the current connection
1. show all databases
1. show all tables
1. pattern matching show tables
1. show schema of customers table
1. show all schemas
1. show index of customer table:
1. show all indexes
1. saving the result of a query into a file
1. output back to the standard output
1. executing SQL statements from a file (in file we have for example *SELECT * FROM genres;*)

## SQLite Tutorial

### Section 1. Simple query

#### SELECT

1. math query
1. tables query
    1. all columns from genres table
    1. column name from genres table
    1. columns FirstName, BirthDate, HireDate from employees table

### Section 2. Sorting rows

#### ORDER BY

1. all columns from genres table, ascending order by column Names
1. all columns from genres table, descending order by column GenreId
1. columns GenreId, Name from tracks table, ascending order by column GenreId, descending order by column Name
1. all columns from genres table, all from genres table order by column number 2
1. columns name, composer from tracks table, order by column composer, show nulls on the records top
1. columns name, composer from tracks table, order by column composer, show nulls on the records bottom

### Section 3. Filtering data

#### Select Distinct

1. column city from customers table, remove duplicate cities from results
1. column city from customers table,, remove duplicate pair city - country from results
1. remove amount of NULLs from result:
    1. column company from customers table - get a lot of NULLs here
    1. column company from customers table - get a single NULL here
