# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

In this assignment, you'll learn to build RESTful APIs using Python's FastAPI framework. You'll create endpoints for managing resources, handle HTTP requests and responses, and implement basic CRUD operations to build a functional web API.

## 📝 Tasks

### 🛠️ Set up FastAPI Project

#### Description
Install FastAPI and create a basic application structure with a root endpoint.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn using pip
- Create main.py with a FastAPI app instance
- Add a GET / endpoint that returns a welcome message in JSON format

### 🛠️ Create Item Management Endpoints

#### Description
Implement CRUD operations for managing items through REST API endpoints.

#### Requirements
Completed program should:

- GET /items - return a list of all items
- POST /items - create a new item from request body
- GET /items/{id} - retrieve a specific item by ID
- PUT /items/{id} - update an existing item
- DELETE /items/{id} - delete an item by ID

### 🛠️ Add Data Models and Validation

#### Description
Use Pydantic models for request and response validation to ensure data integrity.

#### Requirements
Completed program should:

- Define an Item model with id, name, and description fields
- Use the model for request/response validation in all endpoints
- Handle validation errors gracefully with appropriate HTTP status codes