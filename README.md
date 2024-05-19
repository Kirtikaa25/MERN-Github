GitHub Clone


A GitHub clone built using the MERN stack (MongoDB, Express, React, Node.js) and GitHub API.


Technologies Used
Frontend: React,Tailwind CSS 
Backend: Node.js, Express.js
Database: MongoDB
Authentication:Passport.js
API: GitHub API

Installation
Prerequisites
Node.js (v12 or later)
npm (v6 or later) or yarn
MongoDB
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/github-clone.git
cd github-clone
Install dependencies:

For the backend:

bash
Copy code
cd backend
npm install
For the frontend:

bash
Copy code
cd ../frontend
npm install
Set up environment variables:

Create a .env file in the backend directory with the following:

env
Copy code
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_client_secret
Run the application:

Start the backend server:

bash
Copy code
cd backend
npm start
Start the frontend development server:

bash
Copy code
cd ../frontend
npm start
The application should now be running at http://localhost:3000.










