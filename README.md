Capstone Project
This is the README file for the Capstone Project. This project consists of two main components: the frontend and the backend.

Prerequisites
Before running this project, make sure you have the following prerequisites installed on your system:

Node.js: Download and install Node.js
MongoDB: Install MongoDB
Getting Started
Clone the project repository to your local machine:
git clone https://github.com/Creative-Me-Sanket/CapstoneProject.git

A. Navigate to the project :
    cd capstone-project

2. Backend Setup
    cd server

3. Create a .env file in the backend directory with the following content:  
    MONGO_PASS="sanket"
    MONGO_USER="khulesanket3939"
    JWT_SECRET="sanket"
    MONGO_URL="mongodb+srv://sanket:sanket@sanket.g8aqbq8.mongodb.net/?retryWrites=true&w=majority"
    PORT=3001

4. Install backend dependencies and start the server:
    npm install
    npm start
    The backend server will start on port 3001.

B. Frontend Setup

1. Navigate to the project :
    cd frontend

2. Install frontend dependencies and start the application:
    npm install
    npm start

# Running the Project
 With both the backend and frontend servers running, you can access the full application by visiting http://localhost:3000 in your web browser. The frontend communicates with the backend via the specified API routes.