# SQL-Analysis-for-Maritime-Operations

A comprehensive database solution for efficient boat management.

Table of Contents

# About the Project
This project focuses on analyzing operational and financial data for a fictional maritime services company (Solent). Using PostgreSQL, I designed a normalized relational database and wrote analytical SQL queries to generate actionable business insights.

The goal of the project is business analysis — understanding revenue patterns, customer behaviour, service utilization, and operational efficiency through structured data.


# Data Model & Design

The database follows a normalized schema to reduce redundancy and ensure reliable analysis. The data model supports efficient querying for business reporting and insight generation.

Included in the repository:

Entity-Relationship Diagram (ERD)

Data Dictionary

# Technologies Used

Database Management System: PostgreSQL
Query Language: SQL

# Getting Started

Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/solent-boat-management.git  
Install PostgreSQL:
Ensure you have PostgreSQL installed on your system.
Import the Database Schema:
Use the provided SQL script to set up the database:
bash
Copy code
psql -U <username> -d <database_name> -f setup.sql  
Usage
Load the database schema and sample data.
Run the queries in queries.sql to:
Retrieve customer and boat details.
Analyze revenue trends.
Manage staff schedules.
Explore the data using tools like pgAdmin or the PostgreSQL command line.
Future Improvements
Add a graphical user interface for easier data interaction.
Implement API endpoints for integration with other systems.
Expand reporting capabilities with advanced analytics.

# Acknowledgments
This project was developed as part of coursework for the Database Systems module. Special thanks to University of Portsmouth and Dr. Val Adamescu for guidance.
