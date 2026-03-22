# Cyber Crime Management System

Backend application to manage cyber crime complaints, track case status, and store evidence securely.

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* MongoDB
* AWS S3
* RESTful API

## Features

* Register and manage cyber crime complaints
* Track complaint status and updates
* Store and retrieve evidence files using AWS S3
* REST APIs for complaint handling and data access
* CRUD operations for case management

## API Endpoints

* GET /complaints → Retrieve all complaints
* POST /complaints → Register new complaint
* PUT /complaints/{id} → Update complaint status
* DELETE /complaints/{id} → Remove complaint

## Project Structure

* Controller → API request handling
* Service → Business logic
* Repository → Data operations
* Entity → Data models

## How to Run

1. Clone the repository
2. Open project in Eclipse or IntelliJ
3. Configure MongoDB connection
4. Configure AWS S3 access keys and bucket
5. Run Spring Boot application
6. Test APIs using Postman

## Author

Mithun K
Java Backend Developer
