# Registration-Login REST API with Spring Boot, MongoDB & JWT Authentication

This is a simple and secure user registration and login REST API built using **Spring Boot**, **MongoDB**, and **JWT (JSON Web Token)** for authentication and authorization.

## Features

- **User Registration**: Allows new users to register with details such as username, email, password, phone, and address. Passwords are securely hashed using BCrypt before saving.
- **User Login**: Validates registered users and returns a JWT token upon successful authentication.
- **JWT Authentication**: Secures endpoints by issuing and validating JWT tokens, enabling stateless and scalable security.
- **User Listing**: Provides an endpoint to list all registered users (with passwords hidden).
- **Error Handling**: Handles common errors such as duplicate registration, invalid login credentials, and internal server errors gracefully.

## Technologies Used

- Java 17 (or your preferred version)
- Spring Boot (Spring Web, Spring Security)
- MongoDB (NoSQL database)
- JWT (io.jsonwebtoken - jjwt 0.11.5)
- Maven build tool

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 17 or later
- Maven 3.6+
- MongoDB (locally installed or a cloud MongoDB service)
- Postman or any REST client to test APIs
