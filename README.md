# Containerized Microservices Deployment

This project demonstrates a simple microservices-based application using Docker Compose, including a frontend service served by Nginx and a backend API service built with Flask.

## Project Structure

- `frontend/`: Contains the Dockerfile, Nginx config, and static files for the frontend.
- `backend/`: Contains the Dockerfile and Flask application for the backend.
- `docker-compose.yml`: Manages both services with Docker Compose.
- `.env`: Stores environment variables.

## Setup and Run

1. **Build and Start Services**:
   ```bash
   docker-compose up --build
