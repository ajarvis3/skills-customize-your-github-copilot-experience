# 📘 Assignment: Database Operations with SQLite

## 🎯 Objective

In this assignment, you'll learn to work with SQLite databases in Python. You'll establish database connections, create tables, and perform CRUD (Create, Read, Update, Delete) operations to manage data persistence in your applications.

## 📝 Tasks

### 🛠️ Set up SQLite Database Connection

#### Description
Create a new SQLite database file and establish a connection using Python's sqlite3 module.

#### Requirements
Completed program should:

- Import the sqlite3 module
- Create or connect to a SQLite database file
- Create a table with appropriate columns (e.g., id, name, description)
- Handle connection properly with context managers

### 🛠️ Implement CRUD Operations

#### Description
Create functions to perform Create, Read, Update, and Delete operations on the database.

#### Requirements
Completed program should:

- INSERT operation to add new records
- SELECT operation to retrieve records (all and by ID)
- UPDATE operation to modify existing records
- DELETE operation to remove records
- Use parameterized queries to prevent SQL injection

### 🛠️ Build a Command-Line Application

#### Description
Create a simple command-line interface that allows users to interact with the database through a menu system.

#### Requirements
Completed program should:

- Display a menu with options for CRUD operations
- Accept user input for data entry
- Display query results in a readable format
- Include error handling for invalid inputs and database errors