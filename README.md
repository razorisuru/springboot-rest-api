# Spring Boot REST API Application

This is a Spring Boot API application built using JDK 17. It provides a RESTful API for managing resources, with capabilities such as creating, reading, updating, and deleting (CRUD) entities.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Testing](#testing)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- RESTful APIs to manage resources.
- CRUD operations for entities.
- Structured error handling.
- JSON response formatting.
- Pagination and filtering support.
- Integrated Swagger documentation.

## Prerequisites
To run this application, ensure you have the following installed:
- **JDK 17**
- **Maven 3.8+**
- **MySQL** (or another database depending on your configuration)

## API Endpoints

The frontend communicates with the following backend endpoints:

- `GET /api/users` - Get all users
- `GET /api/users/:id` - Get a single user
- `POST /api/users` - Add a new user
- `PUT /api/users/:id` - Update a user
- `DELETE /api/users/:id` - Delete a user

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/razorisuru/springboot-rest-api
   cd springboot-rest-api

