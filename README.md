# Ride-Hailing Application

This is a ride-hailing application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to book rides, track drivers in real-time, and manage their profiles.

## Features
- User and Captain (Driver) authentication
- Real-time location tracking
- Ride booking and management
- Live driver tracking
- Fare calculation
- Socket-based real-time communication

## Installation

### Prerequisites
- Node.js
- MongoDB

### Backend Setup
1. Navigate to the `Backend` directory:
   ```bash
   cd Backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and configure your environment variables.
4. Start the server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend application:
   ```bash
   npm run dev
   ```

## API Endpoints
- **POST /api/register**: Register a new user
- **POST /api/login**: Log in a user
- **GET /api/profile**: Get user profile
- **GET /api/logout**: Log out a user

## Demo
- To see the application in action, follow the installation steps above and navigate to `http://localhost:3000` in your browser.

## License
This project is licensed under the MIT License.
