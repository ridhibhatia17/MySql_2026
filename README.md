# MySQL Learning Notes


A beginner-friendly collection of notes to learn database fundamentals, SQL basics, MySQL setup, core terminology, data types, and essential database-level commands.

## Learning Path

Follow the files in this order:

1. [01_Database_Explained.md](01_Database_Explained.md)
2. [02_Sql_Basics.md](02_Sql_Basics.md)
3. [03_Install_MySql.md](03_Install_MySql.md)
4. [04_Learn_Basic_Database_Terminologies.md](04_Learn_Basic_Database_Terminologies.md)
5. [05_MySql_Datatypes_Mastery.md](05_MySql_Datatypes_Mastery.md)
6. [06_Sql_Database_Commands.md](06_Sql_Database_Commands.md)

## What You Will Learn

- What databases are and why they are important
- Core SQL command categories (DDL, DML, DCL, TCL)
- How to install and configure MySQL on Windows
- Essential database terms like schema, query, index, and result set
- MySQL data types for numbers and text, with examples
- How to create, list, select, check, and drop databases safely

## Suggested Study Flow

1. Read one file at a time.
2. Run every SQL example in MySQL Workbench or MySQL Shell.
3. Keep your own practice file with sample databases, tables, and queries.
4. Revisit the data types and database commands sections before creating real schemas.

## Prerequisites

- A Windows machine
- MySQL Server installed
- MySQL Workbench (recommended)

## Quick Start

After installation, test your setup with:

```sql
SELECT VERSION();
```

If the command returns a version number, your MySQL setup is working.

Then try a quick database workflow:

```sql
CREATE DATABASE practice_db;
SHOW DATABASES;
USE practice_db;
SELECT DATABASE();
DROP DATABASE practice_db;
```

## Notes

- These notes are focused on MySQL fundamentals.
- The examples are beginner-oriented and can be expanded for real-world projects.
- Practice destructive commands (like DROP DATABASE) only on test databases.
