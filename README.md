# project_20250508_051400_6909b257
A modern full-stack template with React (Vite + Tailwind CSS) frontend and FastAPI backend.

## Features

### Frontend
- React with Vite for fast development
- Tailwind CSS for styling
- React Router for navigation
- Axios for API calls
- Environment variable configuration
- Modern project structure

### Backend
- FastAPI with health check endpoint
- CORS configuration
- Simple and clean structure

### Docker Support
- Dockerfile for frontend
- Dockerfile for backend
- docker-compose.yml for easy development
- Hot-reload support for both frontend and backend

## Getting Started

### Using Docker (Recommended)
```bash
docker-compose up
```
This will start both frontend and backend services:
- Frontend: http://localhost:5173
- Backend: http://localhost:8000

### Manual Setup

#### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

#### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

## API Documentation
Once the backend is running, visit:
- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc
- Health Check: http://localhost:8000/health
