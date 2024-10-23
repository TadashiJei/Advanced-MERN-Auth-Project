# Advanced MERN Auth Project

This project is an advanced MERN (MongoDB, Express, React, Node.js) authentication system. It features:

- Email verification
- Password recovery
- Welcome emails
- Protected routes

## Features

### Backend Setup
- 🔧 Backend server configuration
- 🗄️ MongoDB Database setup
- 🔐 Signup endpoint
- 📧 Sending verification emails for account validation
- 🔍 Verify Email endpoint
- 📄 Building a Welcome Email template
- 🚪 Logout endpoint
- 🔑 Login endpoint
- 🔄 Forgot Password endpoint
- 🔁 Reset Password endpoint
- ✔️ Check Auth endpoint

### Frontend Setup
- 🌐 Frontend server configuration
- 📋 Signup page UI
- 🔓 Login page UI
- ✅ Email verification page UI
- 📤 Implementing Signup functionality
- 📧 Implementing Email verification
- 🔒 Protecting routes after login
- 🔑 Implementing login functionality
- 🏠 Dashboard page
- 🔄 Implementing Forgot Password functionality

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/TadashiJei/Advanced-MERN-Auth-Project/
cd Advanced-MERN-Auth-Project
```

### 2. Install Dependencies
```bash
npm install
```
### 3. Setup the .env file
Create a .env file in the root directory and add the following variables:
```bash
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token
MAILTRAP_ENDPOINT=https://send.api.mailtrap.io/

CLIENT_URL=http://localhost:5173
```
### 4. Run the App Locally
To build the project:
```bash
npm run build
```
To start the app:
```bash
npm run start
```


