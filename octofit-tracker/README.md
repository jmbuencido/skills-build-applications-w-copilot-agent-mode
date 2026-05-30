# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js + Express + TypeScript, and MongoDB.

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
└── backend/           # Node.js + Express + TypeScript API
```

## Architecture

- **Frontend**: React 19 with Vite (Port: 5173)
- **Backend**: Node.js + Express + TypeScript (Port: 8000)
- **Database**: MongoDB (Port: 27017)

## Prerequisites

- Node.js (v18+)
- npm or yarn
- MongoDB (running locally or remote connection)

## Installation

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
```

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
```

## Running the Application

### Start MongoDB
```bash
mongod
```

### Start Backend Server
```bash
cd octofit-tracker/backend
npm run dev
```

The backend API will be available at `http://localhost:8000`

### Start Frontend Development Server
```bash
cd octofit-tracker/frontend
npm run dev
```

The frontend will be available at `http://localhost:5173`

## Development Commands

### Backend
- `npm run dev` - Start development server with ts-node
- `npm run build` - Compile TypeScript to JavaScript
- `npm start` - Run compiled JavaScript
- `npm run type-check` - Check TypeScript types

### Frontend
- `npm run dev` - Start Vite development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## API Endpoints

- `GET /` - API welcome message
- `GET /health` - Health check endpoint with MongoDB status

## Environment Variables

Create a `.env` file in the backend directory if needed:

```
MONGODB_URI=mongodb://localhost:27017/octofit-tracker
PORT=8000
```

## License

MIT
