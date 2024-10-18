# EmployWise Assignment

This project is a React application that integrates with the Reqres API to perform basic user management functions.

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Yashwanth023/EmployeeWise_Assignment.git
   ```

2. Navigate to the project directory:
   ```
   cd employwise-assignment
   ```

3. Install dependencies:
   ```
   npm install
   ```

## Running the Application

To start the development server:

```
npm start
```

The application will be available at `http://localhost:3000`.

## Features

- User authentication
- List all users with pagination
- Edit user details
- Delete users
- Client-side search and filtering

## Login Credentials

Use the following credentials to log in:

- Email: eve.holt@reqres.in
- Password: cityslicka

## Technologies Used

- React
- React Router
- Axios
- Material-UI

## Assumptions and Considerations

- The Reqres API is a mock API, so some operations (like delete and update) don't actually modify the data on the server.
- The application uses local storage to persist the authentication token. In a production environment, more secure methods should be considered.
- Error handling is basic and can be improved for a production-ready application.

