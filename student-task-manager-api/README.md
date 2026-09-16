# Student Task Manager API

A beginner-friendly REST API built with Java and Spring Boot to manage student tasks.

## Features
- Create, read, update and delete tasks
- RESTful API endpoints
- In-memory storage for easy setup
- Maven project structure
- Clean controller, service and model layers

## Tech Stack
- Java 17
- Spring Boot
- Spring Web
- Maven

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/tasks` | Get all tasks |
| GET | `/api/tasks/{id}` | Get a task by ID |
| POST | `/api/tasks` | Create a task |
| PUT | `/api/tasks/{id}` | Update a task |
| DELETE | `/api/tasks/{id}` | Delete a task |

## Run the Project

```bash
mvn spring-boot:run
```

The API runs at `http://localhost:8080`.

## Example POST Request

```json
{
  "title": "Learn Git",
  "description": "Practice Git commands and GitHub",
  "completed": false
}
```

This is a practice project created while learning Git, Java and Spring Boot.
