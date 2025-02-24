# BackEnd_Authorization


# Backend Authorization Project

This is a simple backend authentication system that provides user **login, logout, and registration functionalities** using **MongoDB, JWT, bcrypt, and Tailwind CSS**.

## Features
- User Registration (Signup)
- User Login with JWT Authentication
- Secure Password Hashing using bcrypt
- Protected Routes with JWT Middleware
- User Logout Functionality

## Technologies Used
- **Node.js & Express** - Backend framework
- **MongoDB & Mongoose** - Database and ORM
- **JWT (JSON Web Token)** - Authentication mechanism
- **bcrypt** - Secure password hashing
- **Tailwind CSS** - Styling (if frontend is included)

## Installation

```sh
# Clone the Repository
git clone https://github.com/Suvarna1612/BackEnd_Authorization.git
cd BackEnd_Authorization

# Install Dependencies
npm install

# Set Up Environment Variables
# Create a .env file in the root directory and add the following:
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

# Run the Server
npm start
```

## API Endpoints

### **User Authentication**
```http
POST   /api/auth/register   # Register a new user
POST   /api/auth/login      # Login and get token
GET    /api/auth/logout     # Logout the user
GET    /api/protected       # Access a protected route
```

## Usage
- **Register a User** by sending a POST request to `/api/auth/register` with `email` and `password`.
- **Login** using `/api/auth/login` to get a JWT token.
- Use the **JWT token** in the `Authorization` header (`Bearer <token>`) to access protected routes.
- **Logout** by hitting `/api/auth/logout`.

## Contact
For any queries, reach out to:
- **Name**: Tekumalla Sarada Suvarna
- **Email**: [saradat1612@gmail.com](mailto:saradat1612@gmail.com)
- **GitHub**: [Suvarna1612](https://github.com/Suvarna1612)

