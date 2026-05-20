# Pet Shelter SQL Analysis System

A relational database management project designed for managing pet shelter operations, adoption tracking, vaccination records, and staff activities using SQL.

This project demonstrates database design, normalization, relational modeling, and analytical SQL querying through a realistic pet shelter management system.

---

## Project Overview

The system was built to simulate the operational workflow of pet shelters and adoption centers. It manages:

* Customer records
* Shelter organizations
* Cat and dog information
* Vaccination tracking
* Staff and training management
* Pet sitting records
* Adoption history

The project focuses on both data organization and analytical querying.

---

## Technologies Used

* MySQL
* SQL
* Relational Database Design

---

## Database Features

### Entity Relationships

The database contains multiple related entities including:

* Customer
* Shelter Organisation
* Cat
* Dog
* Staff
* Training
* Vaccination Records
* Adoption Records

The schema uses:

* Primary Keys
* Foreign Keys
* One-to-Many Relationships
* Data Integrity Constraints

---

## Key SQL Concepts Demonstrated

This project demonstrates:

* INNER JOIN
* LEFT JOIN
* UNION / UNION ALL
* Subqueries
* EXISTS / NOT EXISTS
* GROUP BY
* HAVING
* Aggregate Functions
* Relational Data Modeling

---

## Example Analytical Queries

### 1. Adoption Tracking Analysis

Combined cat and dog adoption records with customer and shelter information to identify adopted pets and their originating organizations.

**Concepts Used:**

* JOINS
* COALESCE
* Relational Mapping

---

### 2. Vaccination Pattern Analysis

Identified cats that received multiple vaccinations using aggregation and grouping logic.

**Concepts Used:**

* GROUP BY
* HAVING
* Subqueries

---

### 3. Pet Availability Monitoring

Used NOT EXISTS queries to identify pets currently available for adoption.

**Concepts Used:**

* NOT EXISTS
* UNION
* Filtering Logic

---

### 4. Shelter Performance Insights

Calculated the total number of rescued pets managed by each shelter organization.

**Concepts Used:**

* Aggregation
* UNION ALL
* COUNT

---

### 5. Vaccination Reporting System

Merged cat and dog vaccination records into a unified pet vaccination report.

**Concepts Used:**

* UNION ALL
* LEFT JOIN
* Data Consolidation

---

## Sample Insights

Some examples of insights generated from the database include:

* Identifying shelters with higher adoption activity
* Tracking vaccination completion rates
* Monitoring pets currently available for adoption
* Evaluating trainer activity and dog training records
* Comparing shelter pet volumes

---

## Learning Outcomes

Through this project, I developed practical experience in:

* Designing normalized relational databases
* Managing structured datasets
* Writing complex analytical SQL queries
* Building scalable database schemas
* Extracting operational insights from relational data

---

## Future Improvements

Potential future enhancements include:

* Building a dashboard using Tableau or Power BI
* Creating a frontend application for shelter management
* Adding stored procedures and triggers
* Implementing role-based access control
* Integrating analytics visualizations

---

## Author

Created as part of a database systems and analytics portfolio project.
