# Database-Migration
This project demonstrates a Database Migration process where data is migrated between two databases  MySQL → PostgreSQL  while ensuring data integrity.

The migration ensures:

✅ Schema creation (Library table).

✅ Data insertion (sample book records).

✅ Migration between databases.

✅ Data integrity verification (row counts match).


Tech Stack :

Python

SQLite (simulating MySQL & PostgreSQL)

Pandas (for data handling)

SQLAlchemy (for database connection & migration)

Tabulate (for pretty table output in Colab)


Features :

📚 Creates a Library table with book records.

🔄 Migrates data from a simulated MySQL DB to a simulated PostgreSQL DB.

🛡️ Verifies data integrity by comparing row counts.

📊 Displays both source and target tables in tabular format.
