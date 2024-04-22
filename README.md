# User Management System Backend

This is a simple user management system backend built using Node.js and MongoDB Cloud. It provides basic CRUD (Create, Read, Update, Delete) operations for managing user data.

## Getting Started

### Prerequisites

Before running the application, you need to have the following installed on your machine:

- Node.js
- MongoDB Cloud account (with a database set up)

### Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the dependencies.
4. Create a `.env` file in the root directory and add your MongoDB Cloud URI. Example: `MONGO_URI=your_mongodb_uri`

### Usage

1. Start the server by running `npm start` or `node server.js` in the terminal.
2. Once the server is running, you can access the API endpoints to manage users.

### API Endpoints

- `GET /users`: Retrieve all users.
- `POST /users`: Create a new user.
- `PUT /users/:id`: Update an existing user by ID.
- `DELETE /users/:id`: Delete a user by ID.

## Built With

- Node.js - JavaScript runtime environment.
- Express.js - Web application framework for Node.js.
- MongoDB - NoSQL database.
- Mongoose - MongoDB object modeling for Node.js.

## Authors

- aditya-7562

