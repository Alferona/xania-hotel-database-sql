# Xania Hotel Booking Database System

## Project Overview

Xania Hotel Booking Database System is a relational database project designed for managing hotel reservations, rooms, customers, staff operations, and payment records.

The project focuses on database architecture, SQL implementation, entity relationship modelling (ERD), normalization, and structured query analysis using Microsoft SQL Server.

This repository contains the database schema, sample datasets, SQL queries, diagrams, and supporting documentation prepared as part of a group-based database systems project.

---

## My Role in the Project

My main responsibility in this project focused on:

- designing SQL table structures
- building relational connections between entities
- creating ERD diagrams
- implementing primary and foreign key relationships
- handling normalization structure
- writing and testing SQL queries
- validating table relationships and data consistency

I also contributed to query testing and structured database documentation.

---

## System Features

The database system supports:

- hotel branch management
- room and room type management
- customer information tracking
- booking and reservation handling
- payment record management
- staff management
- revenue-related query analysis

---

## Database Design

### Main Entities

- Branch
- RoomType
- Room
- Customer
- Staff
- Booking
- Payment

### Database Concepts Used

- Relational Database Design
- ERD Modelling
- Normalization
- Primary & Foreign Keys
- One-to-Many Relationships
- SQL Constraints
- Data Integrity

---

## Technologies Used

- SQL
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- ERD Modelling
- Relational Database Systems

---

## SQL Operations Demonstrated

This project includes practical use of:

- CREATE TABLE
- INSERT INTO
- SELECT Queries
- INNER JOIN
- LEFT JOIN
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- Filtering Conditions
- Revenue & Reservation Analysis Queries

---

## Project Structure

```text
xania-hotel-database-sql/
├── .gitignore
├── queries.sql
├── README.md
├── sample-data.sql
├── schema.sql
├── diagrams/
│   ├── dbms-relationship-diagram.png
│   └── entitiy-relationship-diagram.png
├── documentation/
│   ├── add-clean-documentation-here.txt
│   ├── database-project-summary.md
│   └── xania-hotel-database-project-summary.pdf
└── screenshots/
    ├── booking-table-query.png
    ├── booking-table.png
    ├── branch-table.png
    ├── customer-table-query.png
    ├── customer-table.png
    ├── payment-table-query.png
    ├── payment-table.png
    ├── room-table-query.png
    ├── room-table.png
    ├── room-type-table.png
    ├── staff-table-query.png
    └── staff-table.png
```

## How to Use

1. Open SQL Server Management Studio or another compatible SQL environment.
2. Create a new database.
3. Run `schema.sql` to create tables.
4. Run `sample-data.sql` to insert sample data.
5. Run `queries.sql` to test the DML queries.

## SQL Features Demonstrated

- `CREATE TABLE`
- `PRIMARY KEY`
- `FOREIGN KEY`
- `INSERT INTO`
- `SELECT`
- `JOIN`
- `LEFT JOIN`
- `WHERE`
- `GROUP BY`
- `HAVING`
- `ORDER BY`
- `SUM`
- `COUNT`
- date filtering

## Diagrams

### Entity Relationship Diagram

![Entity Relationship Diagram](diagrams/entitiy-relationship-diagram.png)

### DBMS Relationship Diagram

![DBMS Relationship Diagram](diagrams/dbms-relationship-diagram.png)

## Screenshots

### Branch Table

![Branch Table](screenshots/branch-table.png)

### Room Type Table

![Room Type Table](screenshots/room-type-table.png)

### Room Table

![Room Table](screenshots/room-table.png)

### Room Table Query

![Room Table Query](screenshots/room-table-query.png)

### Customer Table

![Customer Table](screenshots/customer-table.png)

### Customer Table Query

![Customer Table Query](screenshots/customer-table-query.png)

### Staff Table

![Staff Table](screenshots/staff-table.png)

### Staff Table Query

![Staff Table Query](screenshots/staff-table-query.png)

### Booking Table

![Booking Table](screenshots/booking-table.png)

### Booking Table Query

![Booking Table Query](screenshots/booking-table-query.png)

### Payment Table

![Payment Table](screenshots/payment-table.png)

### Payment Table Query

![Payment Table Query](screenshots/payment-table-query.png)

## Documentation

- [Database Project Summary](documentation/database-project-summary.md)
- [Xania Hotel Database Project Summary PDF](documentation/xania-hotel-database-project-summary.pdf)

What I Learned

Through this project, I improved my understanding of:

structured database design
SQL query logic
normalization techniques
relational schema architecture
database relationships
query optimization basics
data organization and integrity

## Future Improvements

stored procedures
SQL views
indexing optimization
triggers and constraints
dashboard integration
application-level database connection
analytics reporting system

