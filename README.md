# Expense Tracker Application

A full-stack expense tracking application built with React, Node.js, Express, and MongoDB.

## Features

- Add, view, and delete expenses
- Categorize expenses
- Visualize expenses using a doughnut chart
- Persistent storage using MongoDB

## Prerequisites

- Node.js (v14 or higher)
- MongoDB (v4.4 or higher)
- npm or yarn

## Setup

1. Clone the repository
2. Install MongoDB and make sure it's running on your system

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the backend directory with:
```
MONGODB_URI=mongodb://localhost:27017/expense-tracker
PORT=5000
```

### Frontend Setup

```bash
cd my-react-app
npm install
```

## Running the Application

1. Start the backend server:
```bash
cd backend
npm start
```

2. In a new terminal, start the frontend:
```bash
cd my-react-app
npm run dev
```

The application will be available at:
- Frontend: http://localhost:5173
- Backend: http://localhost:5000

## Technologies Used

- Frontend:
  - React
  - Vite
  - Chart.js
  - React-Chartjs-2

- Backend:
  - Node.js
  - Express
  - MongoDB
  - Mongoose 