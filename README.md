# Copilot Bootcamp Monorepo

This is a monorepo containing a React frontend and a Node.js backend with an in-memory SQLite database.

## Project Structure

```
copilot-bootcamp-starter/
├── packages/
│   ├── frontend/     # React frontend
│   └── backend/      # Node.js backend with in-memory database
├── package.json      # Root package.json for monorepo management
└── README.md         # This file
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm run install:all
```

### Running the Application

Start both frontend and backend concurrently:

```bash
npm start
```

Or run them separately:

```bash
# Start frontend only
npm run start:frontend

# Start backend only
npm run start:backend
```

## Frontend

The React frontend runs on http://localhost:3000 and communicates with the backend API.

## Backend

The Node.js backend runs on http://localhost:5000 and provides the following endpoints:

- `GET /api/items` - Get all items from the database
- `POST /api/items` - Add a new item to the database

The backend uses an in-memory SQLite database that is initialized with sample data on startup.
