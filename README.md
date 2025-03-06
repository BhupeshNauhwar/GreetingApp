🚀 GreetingApp

Welcome to GreetingApp, a Spring Boot application designed to manage and showcase greeting messages with authentication support. This project integrates Swagger API documentation to make API exploration effortless.

📜 Table of Contents

🔹 Features

📌 API Endpoints
 
📖 Learning from This Project

💡 Technologies Used

🔹 Features

✅ CRUD Operations for Greeting Messages.

✅ User Authentication using JWT-based login and registration.

✅ H2 In-Memory Database for easy data storage.

✅ Spring Security Configuration allowing unrestricted API access.

✅ Swagger Integration for interactive API testing.
✅ RESTful API Architecture for structured responses.

📌 API Endpoints

📝 Greeting Controller

| Method | Endpoint                                  | Description                          |
|--------|-------------------------------------------|--------------------------------------|
| 🟢 GET    | `/greeting`                              | Get a greeting message              |
| 🔵 PUT    | `/greeting`                              | Update a greeting                   |
| 🟠 POST   | `/greeting`                              | Create a new greeting               |
| 🔴 DELETE | `/greeting`                              | Delete a greeting                   |
| 🔵 PUT    | `/greeting/greeting-update/{id}`         | Update a specific greeting by ID    |
| 🟢 GET    | `/greeting/greeting-save`                | Save a greeting                     |
| 🟠 POST   | `/greeting/greeting-save`                | Save a new greeting                 |
| 🟢 GET    | `/greeting/service`                      | Fetch greeting from a service       |
| 🟢 GET    | `/greeting/param`                        | Get greeting with query parameters  |
| 🟢 GET    | `/greeting/greeting-find/{id}`           | Find a greeting by ID               |
| 🟢 GET    | `/greeting/greeting-all`                 | Retrieve all greetings              |
| 🔴 DELETE | `/greeting/greeting-delete/{id}`         | Delete a greeting by ID             |

🔐 Auth Controller

| Method | Endpoint            | Description                  |
|--------|---------------------|------------------------------|
| 🟠 POST   | `/auth/register`    | Register a new user         |
| 🟠 POST   | `/auth/login`       | Authenticate user login     |
| 🟢 GET    | `/auth/verify`      | Verify user authentication  |



📖 Learning from This Project

🔹 Spring Boot Basics - REST API development, dependency injection, and configuration.

🔹 Spring Security - Implementing authentication & authorization with JWT.

🔹 Swagger (OpenAPI 3.0) - Auto-generating API documentation.

🔹 H2 Database - Managing data in an in-memory database.

🔹 Spring Boot Configuration - Using application.properties for database and email setup.

🔹 Handling API Requests - Implementing GET, POST, PUT, and DELETE requests.

💡 Technologies Used

🚀 Spring Boot - Backend framework
🔐 Spring Security - Authentication & Authorization
🗄 H2 Database - In-memory database for testing
🔧 Maven - Build automation tool
📑 Swagger (OpenAPI 3.0) - API documentation
💾 JPA & Hibernate - ORM for data management

