# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a simple REST API using the FastAPI framework in Python. You will design endpoints, handle requests, and return JSON responses.

## 📝 Tasks

### 🛠️ Task 1: Set Up FastAPI Project

#### Description
Set up a new Python project with FastAPI and Uvicorn. Create a basic FastAPI app that runs a web server and responds to a simple GET request.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main.py file with a FastAPI app
- Add a root endpoint ('/') that returns a welcome message as JSON


### 🛠️ Task 2: Create REST Endpoints

#### Description
Add endpoints to your FastAPI app to manage a list of items (e.g., books, tasks, or users). Implement GET and POST methods.

#### Requirements
Completed program should:

- Add a GET endpoint to list all items
- Add a POST endpoint to add a new item (accept JSON input)
- Store items in a Python list (in-memory)
- Return appropriate JSON responses for each endpoint

---

**Extension Ideas:**
- Add endpoints for updating and deleting items
- Use Pydantic models for data validation
- Add error handling for invalid requests

**Learning Objectives:**
- Understand REST API concepts
- Use FastAPI to build web APIs
- Handle HTTP requests and JSON data in Python
