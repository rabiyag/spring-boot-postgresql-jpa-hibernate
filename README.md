# Spring Boot PostgreSQL JPA Hibernate

This project demonstrates how to integrate **Spring Boot** with **PostgreSQL** using **JPA** and **Hibernate** for persistence management. It provides a simple example of creating, reading, updating, and deleting entities using Spring Data JPA and Hibernate.


## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Running the Application](#running-the-application)
- [Usage](#usage)

## Features
- Integration of **Spring Boot** with **PostgreSQL** using **JPA** and **Hibernate**.
- CRUD (Create, Read, Update, Delete) operations for entities.
- Simple data model and REST API to interact with the database.

## Technologies Used
- **Spring Boot** (backend framework)
- **PostgreSQL** (database)
- **JPA** (Java Persistence API)
- **Hibernate** (ORM framework)
- **Maven** (dependency management)

## Project Structure
```
src/main/java
    ├── controller      # Controller handling API requests
    ├── model           # Model representing data entities
    ├── repository      # Spring Data JPA repository interfaces
    ├── service # Service layer to handle business logic 
src/main/resources
    └── application.properties # Database connection and application configuration

```

## Prerequisites
- **JDK 8** or higher
- **Maven** for dependency management
- **PostgreSQL** database

## Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/rabiyag/spring-boot-postgresql-jpa-hibernate.git
   cd spring-boot-postgresql-jpa-hibernate
   ```


2. **Set up the PostgreSQL database**:
   - Create a new database in PostgreSQL:
    ```sql
    CREATE DATABASE springbootdb;
    ```
   
3. **Configure database connection**:
   - Update the application.properties file with your PostgreSQL connection details

4. **Build the project with Maven**:
   ```bash
   mvn clean install
   ```

## Running the Application
1. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

2. **Access the application**:
   - The application will be available at http://localhost:8080:
  

## Usage
The project provides a RESTful API for interacting with the PostgreSQL database. You can perform CRUD operations by sending requests to the endpoints exposed by the controllers.
