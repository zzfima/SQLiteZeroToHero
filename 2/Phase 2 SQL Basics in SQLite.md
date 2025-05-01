# SQLiteZeroToHero
SQLite Zero To Hero

## Phase 2: SQL Basics in SQLite

### 3. Data Definition Language (DDL)

1. In created test.db practice DDL commands for contacts table:
1. edit database: sqlite3.exe .\test.db
1. for creating table: CREATE TABLE contacts (contact_id INTEGER PRIMARY KEY, first_name TEXT NOT NULL, last_name TEXT NOT NULL, email TEXT NOT NULL UNIQUE, phone TEXT NOT NULL UNIQUE);
1. for list tables: .tables
1. for rename table: ALTER TABLE contacts RENAME TO contacts1;
1. for delete table: DROP TABLE contacts

### 4. Data Manipulation Language (DML) (continue of previous 3)

1. for inserting values: INSERT INTO contacts (contact_id, first_name, last_name, email, phone) VALUES (1, 'Alex', 'Don', 'al@gh.com', '11234'), (2, 'Tim', 'Fom', 'tm@gh.com', '435345'), (3, 'Lom', 'Kon', 'lm@gh.com', '65656');
1. for change value within specific cretaria: UPDATE contacts SET phone = '1111' WHERE contact_id == 1;
1. for delete row: DELETE FROM contacts WHERE phone == '1111';