## College Library Database (Oracle SQL Project)
A simple college library management system implemented using Oracle SQL.
> This project was created as part of the Database Programming (CT1353) course at King Saud University.

The main goal of this project is to design and implement a relational database that efficiently manages information about books, authors, customers, and checkouts, enabling smooth operations such as lending, tracking, and querying data.

## Project Overview
The database stores and manages library data, including patrons, authors, and borrowed books.
It supports essential library functions such as borrowing tracking, book lookup, and author-book relationships.

**Main Objectives**
- Create a structured library database using Oracle SQL.
- Apply database normalization and relational integrity constraints.
- Execute advanced SQL queries with functions like MAX, AVG, and COUNT.
- Demonstrate understanding of relationships between multiple tables.

## Database Design
The project contains four main tables:
- Table	Description
- **Customers**	Stores patron details (name, phone number).
- **Authors**	Contains author information.
- **Book**	Stores book details and links to authors.
- **Checkout**	Tracks borrowed books and checkout dates.
Each table includes primary and foreign key constraints to ensure relational integrity.
The relationships follow a one-to-many model between authors and books, and between customers and checkouts.

## Features
- Create and populate relational tables
- Enforce integrity with primary and foreign keys
- Execute various SQL operations:
- Filtering and sorting data
- Joining multiple tables
- Using aggregate functions (MAX, COUNT, AVG)
- Generate reports using VIEW queries
- Retrieve analytical insights such as:
- Most borrowed books
- Books never checked out
- Average checkouts per book
- Checkout activity per year

## How It Works
- Tables are created and populated with sample data.
- Relationships between entities are defined using foreign keys.
- Queries and reports are executed to retrieve insights.
- A custom SQL View is created to display joined results from all tables.
- All SQL commands and queries are documented in a separate .sql file in this project.

## Technologies Used
- Oracle SQL
- SQL Developer
- Relational Database Concepts
- Joins, Aggregations, and Views

## Author
**Manar Salem**  
Programming and Database Student  
[https://github.com/Manars](https://github.com/Manars)
