# API Documentation

## Overview
This is a REST API built with Node.js and MongoDB, designed to manage resources effectively. It allows users to create, read, update, and delete (CRUD) operations on various entities.

## Base URL
The base URL for the API is: `https://api.example.com`

## Endpoints

### 1. Users

- **GET /users**  
  Retrieve a list of users.

- **GET /users/{id}**  
  Retrieve a user by ID.

- **POST /users**  
  Create a new user.

- **PUT /users/{id}**  
  Update a user by ID.

- **DELETE /users/{id}**  
  Delete a user by ID.

### 2. Products

- **GET /products**  
  Retrieve a list of products.

- **GET /products/{id}**  
  Retrieve a product by ID.

- **POST /products**  
  Create a new product.

- **PUT /products/{id}**  
  Update a product by ID.

- **DELETE /products/{id}**  
  Delete a product by ID.

### 3. Orders

- **GET /orders**  
  Retrieve a list of orders.

- **GET /orders/{id}**  
  Retrieve an order by ID.

- **POST /orders**  
  Create a new order.

- **PUT /orders/{id}**  
  Update an order by ID.

- **DELETE /orders/{id}**  
  Delete an order by ID.

## Testing Guide

### Prerequisites
- Node.js installed.
- MongoDB installed and running.
- Postman or any other API client for testing.

### Steps to Test the API
1. Clone the repository using `git clone https://github.com/dev-nidhi-codes/rest-api-mongodb.git`.
2. Navigate to the project directory: `cd rest-api-mongodb`.
3. Install the dependencies: `npm install`.
4. Start the server: `npm start`.
5. Open Postman (or your preferred API client).
6. Send requests to the API endpoints as described above.

### Example Test Cases
1. **User Creation**:  
   - Endpoint: `POST /users`  
   - Body: `{ "name": "John Doe", "email": "john@example.com" }`
   - Expected Response: `201 Created`

2. **Product Retrieval**:  
   - Endpoint: `GET /products/1`  
   - Expected Response: `200 OK` and the product object.

3. **Order Deletion**:  
   - Endpoint: `DELETE /orders/1`  
   - Expected Response: `204 No Content`

## Conclusion
Use this documentation to understand how to effectively work with the API and carry out testing procedures.