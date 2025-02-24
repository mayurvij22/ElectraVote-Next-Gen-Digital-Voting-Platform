# MERN Voting Application

A simple voting application built using the MERN (MongoDB, Express, React, Node.js) stack. It allows users to create polls, vote on options, and view results in real-time.

## Features
- Create a new poll with multiple options  
- Vote on an existing poll  
- View real-time poll results  
- User authentication (Optional)  
- Admin panel for managing polls (Optional)  

## Technologies Used
- **Frontend**: React, Axios, Tailwind CSS  
- **Backend**: Node.js, Express.js, MongoDB, Mongoose  
- **Database**: MongoDB (Atlas or Local)  
- **Authentication (Optional)**: JWT, bcrypt  

## Installation & Setup

### 1. Clone the Repository
```sh
git clone <repository-url>
cd mern-voting-app
2. Backend Setup
sh
Copy
Edit
cd backend
npm install
Create a .env file in the backend folder and add:

env
Copy
Edit
MONGO_URI=<your-mongodb-connection-string>
PORT=5000
Run the backend:

sh
Copy
Edit
npm start
3. Frontend Setup
sh
Copy
Edit
cd frontend
npm install
npm start
