# REST API implementation

Implementing REST API for a Task Management System

**To be Implemented using the following Frameworks :**

- [ ] FAST API
- [ ] Nodejs
- [ ] Go
- [ ] SpringBoot

1. **User Authentication**: Implement user authentication and authorization using JWT (JSON Web Tokens) or OAuth. This will allow users to sign up, log in, and access their own tasks.

2. **Task CRUD Operations**: Create endpoints for users to perform CRUD (Create, Read, Update, Delete) operations on tasks. For example:
   - `GET /tasks`: Retrieve all tasks for the authenticated user.
   - `POST /tasks`: Create a new task.
   - `GET /tasks/:id`: Retrieve a specific task by its ID.
   - `PUT /tasks/:id`: Update a task.
   - `DELETE /tasks/:id`: Delete a task.

**Features to be implemented :**

- [ ] Task Filtering and Sorting
- [ ] Task Assignmetns
- [ ] Task Comments
- [ ] Task Due Date Reminders (push notifications)
- [ ] Task Categories or Tags
- [ ] Rate Limiting