# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API in Python using FastAPI. Practice defining HTTP endpoints, accepting and validating JSON data, and returning appropriate responses.

## 📝 Tasks

### 🛠️ Create and Run a FastAPI Application

#### Description
Create a FastAPI application and run it locally so that clients can send it HTTP requests.

#### Requirements
Completed program should:

- Create a FastAPI application that can be started with Uvicorn.
- Provide a `GET /health` endpoint that returns a JSON response indicating the API is running.
- Open FastAPI's interactive API documentation and confirm that the health endpoint responds successfully.


### 🛠️ Add Book Endpoints

#### Description
Create REST endpoints for managing a collection of books. Store the books in memory while the application runs.

#### Requirements
Completed program should:

- Provide endpoints to list all books and retrieve one book by its ID.
- Provide endpoints to create a book, update a book, and delete a book.
- Use the appropriate HTTP methods (`GET`, `POST`, `PUT`, and `DELETE`) and return JSON responses.
- Return a `404 Not Found` response when a requested book ID does not exist.


### 🛠️ Validate Book Data

#### Description
Define a Pydantic model for books and use it to validate data sent when a book is created or updated.

#### Requirements
Completed program should:

- Require each book to have a non-empty title and an author.
- Return a `422 Unprocessable Entity` response when a request body fails validation.
- Return a suitable success status code for creating and deleting a book.
- Test the endpoints with valid and invalid requests using the interactive API documentation.
