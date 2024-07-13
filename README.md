# ToDoRESTful

Build a Todos REST API with Express.js

Objective:
Your task is to create a RESTful API for managing todos using Express.js. This API will allow users to perform various operations on their todo items. Additionally, you'll create a home endpoint that serves a welcoming message using EJS.

Requirements:

Endpoints:
GET /todos: Retrieve all todos.
GET /todos/completed: Retrieve all completed todos.
GET /todos/:id: Retrieve a specific todo by its ID.
POST /todos: Create a new todo.
PUT /todos/completed: Mark a specific todo as completed.
DELETE /todos/:id: Delete a specific todo.

Home Endpoint:
GET /: Serve a welcoming message using an EJS template.


Todo Structure:
Each todo should have the following properties:
title (string)
dueDate (string, formatted as YYYY-MM-DD)
description (string)
isCompleted (boolean)

Data Storage:
Initially, store the todos in a local JSON file.

