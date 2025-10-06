# User API Database

A backend API built with Node.js and Express.js, designed to manage user data. This application allows for the creation, retrieval, updating, and deletion of user information, providing a foundational structure for user management systems.


## Features

* **User Registration**: Allows new users to create an account.
* **User Authentication**: Secure login and session management.
* **CRUD Operations**: Create, Read, Update, and Delete user profiles.
* **Data Validation**: Ensures data integrity and validation.
* **Database Integration**: Stores user data in a MongoDB database.


## Tech Stack

* **Backend**: Node.js, Express.js
* **Database**: MongoDB (with Mongoose ORM)
* **Authentication**: JWT (JSON Web Tokens)
* **Environment Variables**: dotenv for configuration management


## Installation

### Prerequisites

Ensure you have the following installed:

* [Node.js](https://nodejs.org/)
* [MongoDB](https://www.mongodb.com/try/download/community) or access to a MongoDB Atlas cluster

### Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/Jahanvi-07/User-Api-DB.git
   cd User-Api-DB
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory and add the following:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Run the application**

   ```bash
   npm start
   ```


## Screenshot

   The API will be accessible at `http://localhost:5000`.

