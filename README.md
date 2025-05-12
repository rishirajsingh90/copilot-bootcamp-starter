# Copilot Bootcamp Starter

A full-stack JavaScript application with React frontend and Node.js backend.

## Project Structure

```
packages/
  ├── backend/       # Express.js backend with SQLite in-memory database
  └── frontend/      # React.js frontend
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Start the development servers:

```bash
npm start
```

This will start both the backend server and the frontend development server.

## Testing

### Backend Tests

To run the backend tests:

```bash
cd packages/backend
npm test
```

### Frontend Tests

To run the frontend tests:

```bash
cd packages/frontend
npm test
```

To view test coverage:

```bash
cd packages/frontend
npm test -- --coverage
```

## API Endpoints

- `GET /api/items` - Get all items
- `POST /api/items` - Create a new item

## Technologies Used

- **Frontend**: React, Axios
- **Backend**: Express.js, SQLite (in-memory)
- **Testing**: Jest, React Testing Library, Supertest