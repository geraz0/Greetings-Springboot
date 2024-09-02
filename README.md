# Greetings Spring Boot Application

## Overview

This is a simple Spring Boot application designed to demonstrate the basic functionality of a RESTful API. The application provides a single endpoint that returns a greeting message.

## Features

- **GET /greeting**: Returns a "Hello, World!" message.

## Prerequisites

- **Java 8 or later**: Ensure you have a compatible Java version installed.
- **Springboot dependencies**: Spring Web & Spring Boot DevTools.
- **Maven**: Used to build and run the project (if you're using Maven).
- **cURL or Postman**: For testing the endpoint.

## Running the Application

1. **Clone the repository** (if applicable) or download the project files.
2. **Navigate to the project directory**:
   ```bash
   cd greetings2

3. **Build and run the application**:
    ```bash
   ./mvnw spring-boot:run
   ```
4. **Access the application**:

- Open a browser or use a tool like Postman to send a GET request to:


   http://localhost:8080/greeting
  
- If you've changed the port, replace 8080 with the correct port number.


## Testing the Application

1. You can test the GET /greeting endpoint using the following curl command:
    ```bash
   curl http://localhost:8080/greeting
   ```
2. Open Postman and create a new GET request. Enter the URL http://localhost:8080/greeting. Send the request, and you should receive the greeting message "Hello, World!".