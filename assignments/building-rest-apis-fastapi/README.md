# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI to manage a collection of books. You will practice defining routes, handling JSON requests and responses, and validating data with Pydantic models.

## 📝 Tasks

### 🛠️ Create the API and List Books

#### Description
Create a FastAPI application that stores a collection of books in memory. Add an endpoint that returns all books and an endpoint that returns one book by its ID.

#### Requirements
Completed program should:

- Start successfully with `uvicorn`
- Define a `Book` model with an integer ID, title, author, and publication year
- Return all books from `GET /books`
- Return one book from `GET /books/{book_id}`
- Return a `404` response when the requested book does not exist


### 🛠️ Add and Update Books

#### Description
Add endpoints that allow clients to create new books and update existing books using JSON request bodies.

#### Requirements
Completed program should:

- Create a book with `POST /books` and return the created book
- Assign a unique ID to each newly created book
- Return an appropriate success status code for a newly created resource
- Update a book with `PUT /books/{book_id}`
- Return a `404` response when an update targets a missing book


### 🛠️ Validate Requests and Delete Books

#### Description
Improve the API by validating incoming data and adding a delete operation. Use FastAPI and Pydantic features to provide helpful errors for invalid requests.

#### Requirements
Completed program should:

- Require non-empty titles and authors
- Reject publication years that are not reasonable four-digit years
- Delete a book with `DELETE /books/{book_id}`
- Return a clear response when a book is deleted
- Return a `404` response when a delete targets a missing book
- Verify the endpoints using the interactive documentation at `/docs` or a REST client
