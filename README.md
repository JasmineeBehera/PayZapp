## A Payments app


PayZapp is a full-stack payment application that enables users to register, authenticate, view their balance, and transfer money securely.

---

## Technology Stack
Frontend: React, Tailwind CSS  
Backend: Node.js, Express  
Database: MongoDB  
Authentication: JWT  

---

## Features
- User registration and login
- Secure authentication
- Balance inquiry
- Fund transfer between users

---

## Setup and Installation

Clone the repository:
```bash
git clone https://github.com/JasmineeBehera/PayZapp.git
cd PayZapp
````

Install backend dependencies, configure environment variables, and start the backend server:

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` directory and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
npm run dev
```

Open a new terminal, install frontend dependencies, and start the frontend:

```bash
cd ../frontend
npm install
npm start
```

The application will be accessible at `http://localhost:3000`.

---

## Project Structure

```
PayZapp/
├── backend
├── frontend
```

---

## Author

Jasminee Behera

```

---



