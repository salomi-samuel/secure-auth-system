# Secure Authentication System 🔐
A simple and secure authentication system using **Node.js**, **Express**, **MongoDB**, and **JWT**.

## ✅ Features
- User Registration with hashed passwords (bcrypt)
- User Login with JWT token generation
- Protected route (Profile) accessible only after login
- Simple frontend using HTML + JS
- MongoDB Atlas for cloud database
- No frameworks used in frontend
  
## 🛠 Technologies
- Node.js
- Express
- MongoDB (Atlas)
- Mongoose
- bcryptjs
- jsonwebtoken
  
## 🚀 How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/salomi-samuel/secure-auth-system.git
   cd secure-auth-system
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a .env file in the root with this content:
   ```bash
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000
   ```
4. Start the server:
   ```bash
   node server.js
   ```
5. Open in Browser:
  - http://localhost:5000/index.html – Register
  - http://localhost:5000/login.html – Login
  - http://localhost:5000/profile.html – View profile (after login)
    
6. 📝 Usage
- Register a new user via the registration page
- Login with your credentials to get a JWT token stored in localStorage
- Access your profile page (protected route)
