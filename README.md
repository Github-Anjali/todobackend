To-Do List Backend

This is the backend implementation of a To-Do List Application.
It provides APIs to manage tasks including creating, updating, deleting, and fetching tasks.

Features:
Create a new task
Get all tasks
Update an existing task
Delete a task

Tech Stack :
Node.js - Runtime environment
Express.js - Web framework
MongoDB - Database


Setup and Run Instructions
Prerequisites
Node.js installed on your system
MongoDB instance running (local or cloud)

Installation
Clone this repository:
git clone https://github.com/Github-Anjali/todobackend.git

Navigate to the project folder:
cd todobackend
Install dependencies:
npm install

Running the Server
Start the backend server with:
npm start

The server will run at:
http://localhost:5000


Environment Variables
Create a .env file in the root of the project with the following variables:
PORT=5000
MONGO_URI=your_mongodb_connection_string
