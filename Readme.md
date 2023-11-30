# Express.js Employee Management API

## Overview

This Express.js API provides endpoints for managing employees using MongoDB as the database.

### Routes

- **Get All Employees**
  - Endpoint: `/employee`
  - Method: GET
  - Description: Retrieves a list of all employees.
  - Example Usage: `GET http://localhost:3000/employee`

- **Create Employee**
  - Endpoint: `/employee`
  - Method: POST
  - Description: Creates a new employee.
  - Example Usage: `POST http://localhost:3000/employee`
  - Body: JSON object with employee details (e.g., firstname, lastname, email, phone, job, dateofjoining).

- **Update Employee**
  - Endpoint: `/employee/:id`
  - Method: PUT
  - Description: Updates an existing employee by ID.
  - Example Usage: `PUT http://localhost:3100/employee/656823c91adaadb77d9336ba`
  - Body: JSON object with updated employee details.

- **Delete Employee**
  - Endpoint: `/employee/:id`
  - Method: DELETE
  - Description: Deletes an employee by ID.
  - Example Usage: `DELETE http://localhost:3100/employee/656823c91adaadb77d9336ba

- **Search Employees**
  - Endpoint: `/searchemployee/:search`
  - Method: GET
  - Description: Searches employees by name.
  - Example Usage: `GET http://localhost:3000/searchemployee/john`

- **Get Employee by ID**
  - Endpoint: `/employee/:id`
  - Method: GET
  - Description: Retrieves details of an employee by ID.
  - Example Usage: `GET http://localhost:3100/employee/656823c91adaadb77d9336ba`

## How to Use

### 1. Clone the Repository

```bash
git clone <repository_url>
```

### 2. Create .env file

```bash
echo "URL='mongodb://127.0.0.1:27017'"
 > .env

```

### 3. Installing the package

```bash
cd server
npm i
```
After completing the installation make sure to check all the dependencies are installed properly

### 4. Running the server 
```bash
npm run dev
```

