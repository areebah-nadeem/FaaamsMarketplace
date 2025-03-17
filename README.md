# 🛒 Faaams Market Shop

**Faaams Market** is a full-stack e-commerce web application that empowers users to create their own shops, add products, and sell online. Designed with a clean user experience and a focus on security, it offers a responsive shopping platform built with the MERN stack.

![Faaams Home Page](./image.png)

## 🚀 Tech Stack

- **Frontend**: React, Bootstrap  
- **Backend**: Node.js, Express  
- **Database**: MongoDB (Mongoose)  
- **Authentication**: JWT (JSON Web Token)  
- **Tools**: Figma (Wireframes), Jira (Agile Task Management)

## ✨ Key Features

- 👤 JWT-based authentication system  
- 🛍️ Create and manage your own shop  
- 📦 Full product CRUD functionality  
- 🔒 Secure access controls  
- 📱 Mobile responsive with Bootstrap  
- ⚙️ RESTful API integration

## 🛠️ Getting Started

Follow these steps to run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/your-username/faaams-market.git
cd faaams-market

# 2. Install backend dependencies
cd server
npm install

# 3. Install frontend dependencies
cd ../client
npm install

# 4. Configure environment variables
# Create a .env file inside /server with:
# MONGO_URI=your_mongo_connection_string
# JWT_SECRET=your_jwt_secret

# 5. Run the backend
cd ../server
npm run dev

# 6. Run the frontend (in a separate terminal)
cd ../client
npm start
