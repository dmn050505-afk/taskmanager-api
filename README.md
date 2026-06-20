# TaskManager API

A RESTful backend application built with Java and Spring Boot for managing users.

## Technologies

* Java 21
* Spring Boot
* PostgreSQL
* Spring Data JPA
* Hibernate
* Maven
* Swagger/OpenAPI
* Git

## Features

* Create users
* Retrieve all users
* Retrieve a user by ID
* Update users
* Delete users
* Input validation
* Global exception handling
* PostgreSQL persistence

## API Endpoints

| Method | Endpoint    | Description       |
| ------ | ----------- | ----------------- |
| GET    | /users      | Get all users     |
| GET    | /users/{id} | Get user by ID    |
| POST   | /users      | Create a new user |
| PUT    | /users/{id} | Update a user     |
| DELETE | /users/{id} | Delete a user     |

## Project Structure

Controller → Service → Repository → PostgreSQL

## Author

Daniel Nunes
