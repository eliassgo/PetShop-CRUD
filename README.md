# PetShop CRUD with Python and Oracle

This project is a Python application for performing CRUD (Create, Read, Update, Delete) operations on a `petshop` table in an Oracle database. The application allows you to create, list, update, and delete pet records.

## Requirements

- Python 3.x
- Python Libraries:
  - `pandas`
  - `oracledb` (or `cx_Oracle`)
- Configured Oracle Database

## Installation

1. **Install the required libraries**:

   ```bash
   pip install pandas oracledb
## Application Menu:

1 - Register Pet (CREATE): Adds a new pet to the table.

2 - List Pets (READ): Lists all registered pets.

3 - Update Pet (UPDATE): Updates an existing pet's details.

4 - Delete Pet (DELETE): Removes a specific pet from the table.

5 - Delete All Pets (DELETE): Removes all records from the table.

6 - Exit: Closes the application.

## CRUD Operations:

Register Pet: Enter the type, name, and age of the pet.

List Pets: Displays all pet records in a table format.

Update Pet: Choose a pet by ID and update its details.

Delete Pet: Choose a pet by ID and remove it from the table.

Delete All Pets: Removes all records from the table and resets the ID to start from 1.
