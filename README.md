# Employee Management REST API

## Project Overview

The Employee Management REST API is a backend application developed using Java and Spring Boot to manage employee information efficiently. The application provides RESTful APIs to perform CRUD (Create, Read, Update, and Delete) operations on employee records.

It uses MySQL to store and manage employee data, making employee information easier to access, update, and maintain.

## Technologies Used

- Java
- Spring Boot
- MySQL
- Hibernate / JPA
- Maven
- RESTful Web Services
- Spring Tool Suite (STS)

## Key Features

- Add new employee records to the database.
- Retrieve employee information.
- View all available employee records.
- Update existing employee details using employee ID.
- Delete employee records using employee ID.
- Integrate the backend application with a MySQL database.
- Perform CRUD operations through REST API endpoints.
- Organize backend functionality using a structured application architecture.

## API Endpoints

### 1. Add Employee
**Method:** POST  
**Endpoint:** `/employee/add`

Adds a new employee record to the database.

### 2. Get All Employees
**Method:** GET  
**Endpoint:** `/employee/all`

Retrieves the available employee records.

### 3. Update Employee
**Method:** PUT  
**Endpoint:** `/employee/update/{id}`

Updates the details of an existing employee using the employee ID.

### 4. Delete Employee
**Method:** DELETE  
**Endpoint:** `/employee/delete/{id}`

Deletes an employee record using the employee ID.

## How the Application Works

1. The client sends an HTTP request to the appropriate REST API endpoint.
2. The Spring Boot application receives and processes the request.
3. The application performs the required employee management operation.
4. Employee data is stored in or retrieved from the MySQL database.
5. The API returns an appropriate response to the client.

## Database Integration

MySQL is used to store employee information. The application connects to the database to perform employee-related operations and maintain records.

## Project Objective

The main objective of this project is to develop a backend application that demonstrates practical knowledge of Java, Spring Boot, RESTful APIs, database connectivity, and CRUD operations.

## Skills Demonstrated

- Core Java and Object-Oriented Programming
- Spring Boot application development
- REST API design and implementation
- CRUD operations
- MySQL database integration
- Backend application development
- Debugging and problem-solving

## Learning Outcomes

Through this project, I gained practical experience in developing RESTful web services, connecting a Spring Boot application with a database, implementing CRUD operations, and understanding the fundamentals of backend application development.

## Future Enhancements

- Add input validation and centralized exception handling.
- Implement authentication and authorization.
- Add pagination, sorting, and searching.
- Write unit tests for service-layer functionality.
- Improve API documentation.

## Author

**Akanksha Singh**

B.Tech in Computer Science and Engineering | 2026 Graduate

Interested in Java Development, Backend Engineering, and Spring Boot Applications.
