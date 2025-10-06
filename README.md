# test_case_backend

Task:
Implement a REST API for a Task Manager system with the following endpoints:

POST /tasks → Create a new task (title, description, due_date, status).

GET /tasks → List all tasks, with optional filters (status, due_date).

PUT /tasks/{id} → Update task.

DELETE /tasks/{id} → Delete task.

Create the Authentication using JWT 

Evaluation:

Clean code structure (use FastAPI or Flask).

Proper request validation (Pydantic schemas if using FastAPI).

Error handling (404, 400, 500).

Unit tests included.
