# SQLite Zero To Hero

SQLite Zero To Hero using www.sqlitetutorial.net

## Getting Started

chinook database:

![alt text](image.png)

SQLite Sample Database

1. open sqlite3: *sqlite3*
1. open sqlite3 and db: *sqlite3 chinook.db*
1. open db: *.open chinook.db*
1. exit: *.quit*

SQLite Commands

1. add a database to the current connection: *attach database "c:\sqlite\db\chinook.db" AS chinook;*
1. show all databases: *.database*
1. show all tables: *.table*
1. pattern matching show tables: *.table '%es'*
1. show schema of customers table: *.schema customers*
1. show all schemas: *.fullschema*
1. show index of customer table: *.index customers*
1. show all indexes: *.index*
1. saving the result of a query into a file: *.output c:/sqlite/db/output.txt*
1. output back to the standard output: *.output*
1. executing SQL statements from a file (in file we have for example *SELECT * FROM genres;*): *.read C:\sqlite\db\commands.txt*
