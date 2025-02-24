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
![image](https://github.com/user-attachments/assets/f6cf1815-32f6-4c8a-a9ca-971e0f7592f6)
![image](https://github.com/user-attachments/assets/4bbee0a6-6b1c-44e0-87e3-02c85ab16f3b)
![image](https://github.com/user-attachments/assets/95e1abbd-a292-4e94-943f-c2a9cf84d583)

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
