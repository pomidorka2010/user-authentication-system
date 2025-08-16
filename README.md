# User Authentication System

## Overview
This project is a simple user authentication system that allows users to register, log in, and securely access protected routes using JSON Web Tokens (JWT).

## Features
- User Registration
- User Login
- Password Hashing with bcrypt
- JWT Token Generation & Verification
- Protected Routes

## Requirements
- Node.js
- Express
- MongoDB (or any other database of your choice)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/user-authentication-system.git
   cd user-authentication-system
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Set up your environment variables (e.g., database connection string, JWT secret).
4. Start the server:
   ```bash
   npm start
   ```

## Usage
- Register a new user at `/api/register`
- Log in at `/api/login`
- Access a protected route by providing the JWT in the authorization header.

## License
This project is licensed under the MIT License.