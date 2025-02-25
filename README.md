Voting System (MERN Stack)

Description

The Voting System is a web application built using the MERN stack (MongoDB, Express.js, React, Node.js) that allows users to vote on various topics securely. The system ensures authentication and prevents duplicate voting.

Features

User authentication (JWT-based login/signup)

Role-based access control (Admin & Voter)

Create and manage voting polls

Cast votes securely (one vote per user per poll)

Real-time results update

Responsive UI using React

Tech Stack

Frontend:

React.js

Redux (for state management)

React Router (for navigation)

Tailwind CSS / Bootstrap (for styling)

Axios (for API requests)

Backend:

Node.js

Express.js

MongoDB (with Mongoose ODM)

JSON Web Tokens (JWT) for authentication

bcrypt.js (for password hashing)

cors (for cross-origin requests)

dotenv (for environment variables)

Installation

Prerequisites

Ensure you have the following installed:

Node.js (>=14.x)

MongoDB

Setup Instructions

1. Clone the repository

git clone https://github.com/your-username/voting-system.git
cd voting-system

2. Backend Setup

cd backend
npm install

Create a .env file inside the backend directory and add the following:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

Run the backend server:

npm start

3. Frontend Setup

cd ../frontend
npm install

Create a .env file inside the frontend directory and add:

REACT_APP_API_URL=http://localhost:5000

Run the frontend server:

npm start

API Endpoints

Authentication

POST /api/auth/register - Register a new user

POST /api/auth/login - Login and get a token

Polls

POST /api/polls - Create a new poll (Admin only)

GET /api/polls - Get all polls

GET /api/polls/:id - Get poll details

POST /api/polls/:id/vote - Vote on a poll

Usage

Sign up or log in.

Browse available polls.

Cast your vote.



## Installation & Setup
![image](https://github.com/user-attachments/assets/f6cf1815-32f6-4c8a-a9ca-971e0f7592f6)
![image](https://github.com/user-attachments/assets/4bbee0a6-6b1c-44e0-87e3-02c85ab16f3b)
![image](https://github.com/user-attachments/assets/95e1abbd-a292-4e94-943f-c2a9cf84d583)


