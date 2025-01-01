# MERN Stack Real-Time Chat App

This is a full-stack real-time chat application built using the MERN stack, which includes **MongoDB**, **Express**, **React**, and **Node.js**, along with **Socket.IO** for real-time functionality.

## Features

- Real-time chat with Socket.IO
- User authentication (JWT-based)
- MongoDB database for data storage
- Fully responsive UI
- Deployed on Render: [Live Demo](https://chat-app-production-6t79.onrender.com/)

## Technologies Used

- **Frontend:** React
- **Backend:** Node.js with Express
- **Database:** MongoDB
- **Real-Time Communication:** Socket.IO

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js
- npm or yarn
- MongoDB instance or Atlas cluster

## Installation and Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Sithum-Bimsara/Mern-Chat-App.git
   cd Mern-Chat-App
Create .env File:

Create a .env file in the root directory with the following contents:

plaintext
Copy code
PORT=8000
MONGO_DB_URI=mongodb+srv://<your-username>:<your-password>@cluster0.oqtav.mongodb.net/chat-app-db?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET=W2wtddXxMRdT9SWvPvsBn0p/qi+uuaORYcLodOv0aEE=
NODE_ENV=development
Replace <your-username> and <your-password> with your MongoDB credentials.

Install Dependencies:

Run the following command to install both backend and frontend dependencies:

bash
Copy code
npm install
npm install --prefix frontend
Run the Application:

To start the server (backend), run:

bash
Copy code
npm run server
To build the frontend, run:

bash
Copy code
npm run build
Access the Application:

Open your browser and go to http://localhost:8000.

Scripts
npm run server: Starts the backend server using Nodemon.
npm run start: Starts the backend server using Node.js.
npm run build: Installs dependencies and builds the frontend.
Project Structure
plaintext
Copy code
Mern-Chat-App/
├── backend/
│   ├── server.js       # Main server file
│   └── ...             # Other backend files (e.g., routes, controllers)
├── frontend/
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── App.js      # Main App file
│   │   └── ...         # Other frontend files
│   └── ...             # Build and public directories
└── .env                # Environment variables
Deployment
The application is deployed at https://chat-app-production-6t79.onrender.com/.

License
This project is licensed under the MIT License.

Acknowledgments
Thanks to all contributors and users for their feedback and support!
