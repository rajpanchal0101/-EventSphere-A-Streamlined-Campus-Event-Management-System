# EventSphere — Event Management System

A platform for event planning, registration, and ticket booking, built with modern design principles and a focus on user experience. Developed using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- Schedule an event
- View upcoming events
- View the event calendar
- Event approval workflow
- Ticket booking with QR code generation

## Tech Used

- React.js
- Node.js
- Express.js
- MongoDB
- JWT for authentication
- QR code generation

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB database

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rajpanchal0101/-EventSphere-A-Streamlined-Campus-Event-Management-System.git
   cd -EventSphere-A-Streamlined-Campus-Event-Management-System
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd client && npm install
   cd ../api && npm install
   ```

3. Create a `.env` file in the `api` directory with your MongoDB connection string:
   ```
   MONGODB_URI=mongodb://localhost/your-database-name
   ```

4. Start the backend:
   ```bash
   cd api
   nodemon start
   ```

5. Start the frontend:
   ```bash
   cd client
   npm run dev
   ```

The frontend runs at `http://localhost:5173` and the backend at `http://localhost:4000`.
