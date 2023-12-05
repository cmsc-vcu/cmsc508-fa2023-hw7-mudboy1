# Homework 7 - Creating a Resume Database

## Overview and Description

This document provides information about a company's employee database, showcasing various tables containing information about individual employees, their specific skill sets, and positions held within the company.

### GitHub Repository

[https://github.com/cmsc-vcu/cmsc508-fa2023-hw7-mudboy1](https://github.com/cmsc-vcu/cmsc508-fa2023-hw7-mudboy1)

## Files

### qmd (Quantum Markdown) File

The `qmd` file contains a Quantum Markdown document providing details about the employee database. It includes code snippets in Python, utilizing libraries such as pandas, tabulate, dotenv, sqlalchemy, and more. The document covers database connection, entity-relationship diagrams, examples of data in the database, sample queries, and a reflection on the assignment.

### ddl (Data Definition Language) File

The `ddl` file contains the Data Definition Language SQL script for creating and defining the structure of the database. It includes sections for dropping tables, creating skills, people, peopleskills, roles, and peopleroles tables, populating these tables, and defining foreign key relationships.

## Entity-Relationship Diagram

The Crows-foot diagram illustrates the relationships between entities in the database. There are two main entities: CUSTOMER and DELIVERY-ADDRESS. The diagram shows relationships between CUSTOMER and ORDER, as well as CUSTOMER and DELIVERY-ADDRESS, indicating that a customer can place one or more orders and use one or more delivery addresses. The entities include attributes such as customer ID, first name, last name, and delivery address ID.

## Examples of Data in the Database

The document provides examples of data in the People, Skills, and Roles tables, offering descriptions of each table and showcasing the entire table content.

### ddl File: hw7-ddl.sql

The `ddl` file contains the SQL script for creating and defining the structure of the database. It includes sections for dropping tables, creating skills, people, peopleskills, roles, and peopleroles tables, populating these tables, and defining foreign key relationships.

Note: The file follows specific instructions regarding table names, primary keys, foreign keys, and data types.

---
