# REST API with MongoDB

## Description
This project is a RESTful API built with Node.js and Express, utilizing MongoDB as the database. It provides endpoints for basic CRUD operations.

## Installation Instructions
1. Clone the repository:
   ```
   git clone https://github.com/dev-nidhi-codes/rest-api-mongodb.git
   ```
2. Navigate to the project directory:
   ```
   cd rest-api-mongodb
   ```
3. Install dependencies:
   ```
   npm install
   ```

## API Endpoints

### 1. Create User
- **POST** `/api/users`
- Body: 
  ```json
  {
    "name": "John Doe",
    "email": "john@example.com"
  }
  ```

### 2. Get All Users
- **GET** `/api/users`

### 3. Get User by ID
- **GET** `/api/users/:id`

### 4. Update User
- **PUT** `/api/users/:id`
- Body:
  ```json
  {
    "name": "Jane Doe"
  }
  ```

### 5. Delete User
- **DELETE** `/api/users/:id`

## Testing Instructions
To run tests for this API, follow these steps:

1. Make sure you have installed all dependencies.
2. Run the test command:
   ```
   npm test
   ```

## License
This project is licensed under the MIT License.
