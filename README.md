# Data Modeling, Engineering, and Analysis Challenge

## Overview

This challenge consists of three main tasks: data modeling, data engineering, and data analysis. Each step builds upon the previous to create a comprehensive analysis of the dataset provided.

---

## Step 1: Data Modeling

1. **Inspect the CSV Files**
   - Review all six provided CSV files to understand their structure, columns, and data relationships.

2. **Create an Entity Relationship Diagram (ERD)**
   - Sketch the relationships between the tables based on primary and foreign keys.
   - Use a tool like QuickDBD to generate the ERD.

---

## Step 2: Data Engineering

1. **Define Table Schemas**
   - Create a schema for each of the six CSV files.
   - Specify:
     - Data types (e.g., `VARCHAR`, `INT`, `DATE`)
     - Primary keys
     - Foreign keys
     - Constraints (e.g., `NOT NULL`, `UNIQUE`)

2. **Handle Primary Keys**
   - Ensure each primary key column has unique values.
   - If necessary, define composite keys for rows requiring a combination of two columns to ensure uniqueness.

3. **Order of Table Creation**
   - Create tables in the correct sequence to avoid foreign key constraint issues.

4. **Import CSV Data**
   - Load each CSV file into its corresponding SQL table.

---

## Step 3: Data Analysis

Perform the following SQL queries to analyze the data:

1. **Employee Details**
   - Retrieve the `employee number`, `last name`, `first name`, `sex`, and `salary` for all employees.

2. **Employees Hired in 1986**
   - List the `first name`, `last name`, and `hire date` for employees hired in 1986.

3. **Department Managers**
   - Retrieve the `manager's employee number`, `last name`, `first name`, `department number`, and `department name` for each department.

4. **Employee Departments**
   - List the `department number`, `employee number`, `last name`, `first name`, and `department name` for all employees.

5. **Employees Named Hercules**
   - Retrieve the `first name`, `last name`, and `sex` of employees whose first name is Hercules and whose last name begins with the letter "B".

6. **Sales Department Employees**
   - List the `employee number`, `last name`, and `first name` of employees in the Sales department.

7. **Sales and Development Departments**
   - Retrieve the `employee number`, `last name`, `first name`, and `department name` of employees in the Sales or Development departments.

8. **Frequency of Last Names**
   - Count the frequency of each `last name` and order the results in descending frequency.

---

## Tools and Technologies

- **QuickDBD**: For creating the ERD.
- **SQL**: For table creation, data import, and analysis.
- **CSV**: File format for the dataset.
- **Database Management System (DBMS)**: To implement schemas and execute queries.

---

## Deliverables

1. Entity Relationship Diagram (ERD) sketch.
2. SQL scripts for:
   - Table creation with schemas.
   - Data import from CSV files.
   - Analysis queries.
3. Results of each query, demonstrating insights extracted from the dataset.

