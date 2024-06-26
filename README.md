# GitHub Clone

## Table of Contents
- [Overview]
- [Features]
- [Installation]
- [Usage]
- [API Endpoints]
- [Technologies Used]

  
## Overview
GitHub Clone is a full-stack web application built using the MERN stack (MongoDB, Express.js, React, Node.js) and integrates with the GitHub API. This application allows users to search for GitHub repositories and users, view detailed information about them, and perform various interactions similar to the actual GitHub platform.

## Features
- Search for GitHub repositories and users
- View detailed information about repositories (e.g., stars, forks, issues)
- View detailed information about users (e.g., repositories, followers)
- User authentication with GitHub OAuth using Passport.js
- Responsive design

## Installation

### Prerequisites
- Node.js
- MongoDB

### Backend Setup
## Clone the repository:
  git clone https://github.com/Kirtikaa25/MERN-Github
   
   cd github-clone
   
## Navigate to the backend directory and install dependencies:

cd backend

npm install

## Create a .env file in the backend directory and add the following variables:

MONGODB_URI=your_mongodb_uri

GITHUB_CLIENT_ID=your_github_client_id

GITHUB_CLIENT_SECRET=your_github_client_secret

JWT_SECRET=your_jwt_secret

## Start the backend server:

npm run dev

## Frontend Setup

Navigate to the frontend directory and install dependencies:

cd ../frontend

npm install

## Start the frontend development server:

npm start

## Usage
Visit http://localhost:3000 in your web browser.

Use the search bar to find GitHub repositories and users.

Click on repositories or users to view detailed information.

Authenticate using your GitHub account to access additional features.


## API Endpoints
Here are some key API endpoints provided by the backend:

GET /api/github/search/repositories?q={query} - Search for repositories

GET /api/github/search/users?q={query} - Search for users

GET /api/github/repositories/{owner}/{repo} - Get repository details

GET /api/github/users/{username} - Get user details

GET /auth/github - Authenticate using GitHub OAuth

GET /auth/github/callback - GitHub OAuth callback

## Technologies Used
Frontend: React,React Router,TailwindCSS

Backend: Node.js, Express.js

Authentication: Passport.js, GitHub OAuth

Database: MongoDB and Mongoose

Version Control: Git

API: GitHub API


## Preview of the app
![171af412-1c56-4eb1-ae12-a1c94e3e138e](https://github.com/Kirtikaa25/MERN-Github/assets/100124517/9e008435-e296-4aa0-a7f4-2de4e88cd145)
![050f0ec3-d406-455c-9ad1-f9872a85ffe0](https://github.com/Kirtikaa25/MERN-Github/assets/100124517/daf48d3a-16ee-4171-b02d-968cd41d1acf)






