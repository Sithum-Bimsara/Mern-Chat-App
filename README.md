# MERN Stack Real-Time Chat Application

This project is a full-stack real-time chat application built with the MERN stack. The frontend is created using React, the backend with Express and Node.js, Socket.IO is used for real-time communication, and MongoDB is the database.

## Live Demo
The application is deployed and available at: [Chat App](https://chat-app-production-6t79.onrender.com/)

## Features
- Real-time messaging with Socket.IO
- User authentication using JWT
- Password hashing with bcryptjs
- Responsive design for mobile and desktop

## Getting Started
Follow the steps below to set up the project locally.

### Prerequisites
Ensure you have the following installed:
- Node.js (https://nodejs.org/)
- MongoDB (https://www.mongodb.com/)
- Git (https://git-scm.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd chat-app-yt
   ```

2. Install dependencies:
   ```bash
   npm install
   cd frontend
   npm install
   ```

3. Create a `.env` file in the `backend` directory with the following variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Start the application:
   - Run the backend server:
     ```bash
     npm run server
     ```
   - Run the frontend:
     ```bash
     cd frontend
     npm start
     ```

### Scripts
- `npm run server`: Starts the backend server with Nodemon.
- `npm start`: Starts the backend server.
- `npm run build`: Installs dependencies and builds the frontend.

### Dependencies
#### Backend
- `bcryptjs`: For password hashing.
- `cookie-parser`: To parse cookies in HTTP requests.
- `dotenv`: To manage environment variables.
- `express`: Web framework for Node.js.
- `jsonwebtoken`: To generate and verify JSON Web Tokens.
- `mongoose`: For interacting with MongoDB.
- `socket.io`: For real-time communication.

#### Dev Dependencies
- `nodemon`: For hot-reloading the backend server during development.

### Deployment
The application is deployed on Render. To deploy your own version:
1. Set up a MongoDB instance (e.g., MongoDB Atlas).
2. Push your repository to a platform like GitHub.
3. Create a Render account and connect your repository.
4. Configure environment variables on Render.

## Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License
This project is licensed under the ISC License.

