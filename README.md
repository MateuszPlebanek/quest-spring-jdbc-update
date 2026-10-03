# Spring JDBC Update Challenge

Project completed as part of a Spring Boot and JDBC exercise.

## Objective

The goal of this project is to update an existing school in a MySQL database using Spring Boot and JDBC.

## Technologies Used

- Java
- Spring Boot
- JDBC
- MySQL
- Thymeleaf
- HTML
- Maven

## Features

- Load an existing school by ID
- Display a pre-filled update form
- Send updated school data with a POST request
- Update the school in the database
- Use `PreparedStatement`
- Use `executeUpdate()`
- Display the updated school after modification

## Routes

Display the update form:

```text
http://localhost:8080/school/update?id=1
```

## How it Works

- The application loads a school using its ID
- The current values are displayed in the update form.
- The user modifies the values.
- The form sends the data with a POST request.
- SchoolRepository.update(...) updates the row in MySQL.
- The updated school displayed
