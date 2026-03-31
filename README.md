# Parks and Recreation Database

This repository contains SQL Server scripts to create and populate a sample database for the Parks and Recreation department.

## Project Overview
The database includes:

- **employee_demographics**: Stores employee personal details (ID, name, age, gender, birth date)  
- **employee_salary**: Stores employee salary, occupation, and department info  
- **parks_departments**: Stores department names with unique IDs  

Sample data is included for all tables. The scripts are designed to be used with **SQL Server Management Studio (SSMS)** for learning and practice purposes.

## How to Use
1. Open the `.sql` files in SSMS.  
2. Execute the scripts in this order:
   1. `DROP DATABASE` (if exists)  
   2. `CREATE DATABASE`  
   3. `USE` the database  
   4. `CREATE TABLE` statements  
   5. `INSERT INTO` statements  
3. You can then run `SELECT * FROM [table_name];` to check the data.

## Purpose
- Practice SQL database creation, table design, and data insertion  
- Learn how to structure related tables for a real-world scenario  
- Query employee and department information for analytics exercises  

## Tables and Sample Data
- **employee_demographics**: Employee IDs, names, ages, gender, birth dates  
- **employee_salary**: Employee IDs, names, occupations, salaries, department IDs  
- **parks_departments**: Department names and IDs  

This database can be used for SQL querying practice, joins, and basic analytics exercises.
