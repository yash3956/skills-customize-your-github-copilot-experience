# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a simple REST API using FastAPI. Students will build endpoints, define request and response models, and run a local API server.

## 📝 Tasks

### 🛠️ Create a Basic FastAPI App

#### Description
Set up a FastAPI application and create a simple root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Create a FastAPI app instance
- Define a root endpoint using the `/` path
- Return a JSON response with a welcome message

### 🛠️ Build CRUD Endpoints

#### Description
Add endpoints to create, read, update, and delete items in an in-memory list.

#### Requirements
Completed program should:

- Create endpoints for `GET`, `POST`, `PUT`, and `DELETE`
- Use request and response models for item data
- Store items temporarily in memory during the session

### 🛠️ Run and Test the API

#### Description
Start the development server and verify that the API behaves correctly with browser or client requests.

#### Requirements
Completed program should:

- Run the FastAPI app locally using `uvicorn`
- Test at least one endpoint successfully
- Show the expected JSON response for a sample request
