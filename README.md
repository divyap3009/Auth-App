# MERN Auth App

A full-stack MERN (MongoDB, Express, React, Node.js) application for user authentication.

### **Deployment:**

The application is deployed and accessible at https://mern-auth-app-two.vercel.app/login

## Features
- User registration and login with email and password
- Secure password storage with bcrypt
- JWT-based authentication and protected routes
- Persistent login sessions using HttpOnly cookies
- Basic user profile management

## Technologies
**Frontend**: React.js, Axios, Bootstrap  
**Backend**: Node.js, Express.js, MongoDB  
**Authentication**: JWT, bcrypt  
**Database**: MongoDB (Mongoose ODM)

## Installation
1. **Clone the repository**:  
   `git clone https://github.com/yourusername/MERN-AUTH_APP.git`  
   `cd MERN-AUTH_APP`

2. **Install dependencies**:  
   `cd backend && npm install`  
   `cd ../frontend && npm install`

3. **Set up environment variables**:  
   Create a `.env` file in the `backend` directory:  
   `PORT=5000`  
   `MONGO_CONN=your_mongodb_connection_string`  
   `JWT_SECRET=your_jwt_secret`

4. **Run the servers**:  
   `cd backend && npm start`  
   `cd ../frontend && npm start`

5. **Access the app** at `http://localhost:3000`.

## Folder Structure
- `backend/`: Node.js/Express server code
- `frontend/`: React.js frontend code
- `README.md`: This README file

## License
Licensed under the MIT License.
