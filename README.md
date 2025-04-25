# API Testing with Postman - Reqres API

This project showcase basic API testing using [Postman](https://www.postman.com) with the fake API from [Reqres.in](https://reqres.in). the goal is to understand HTTP request methods (GET, POST, PUT, PATCH, DELETE), how to use test scripts, and how to manage enviroments in Postman.

## API Request Overview

### 1. GET /api/users?page=2
 - Check user list
 - status 200

### 2. POST /api/users
 - Create user
 - Status 201
 - Check id and createdAT

### 3. PUT /api/users/2
 - Update user full
 - Status 200
 - Check updatedAT

### 4. PATCH /api/users/2
 - Update user partial (job only)
 - Status 200
 - Check job and updatedAt

### 5. DELETE /api/users/2
 - Delete user
 - status 204