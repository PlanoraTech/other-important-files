![Image](./planora-logo-white-github.png)
# Planora
This repository contains important files related to **Planora**, a comprehensive all-in-one institution management system.

## Database Model: planora.png
The database model of the project is represented visually in the image below.

![Database Model](./planora.png)

This diagram provides a detailed view of the database schema, including tables, relationships, and key data structures used within the application.

## Database Dump: planora-dump.sql
The `planora-dump.sql` file contains the complete PostgreSQL dump of the database, including the database creation, tables, relationships, and sample data.

### How to Use the SQL Dump
To import the database structure into your PostgreSQL instance, you can use the following command:
```bash
psql -U your-username -f path/to/planora-dump.sql
