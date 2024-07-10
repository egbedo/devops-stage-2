# Full-Stack FastAPI and React Template

Welcome to the Full-Stack FastAPI and React template repository. This repository serves as a demo application for interns, showcasing how to set up and run a full-stack application with a FastAPI backend and a ReactJS frontend using ChakraUI.

## Project Structure

The repository is organized into two main directories:

- **frontend**: Contains the ReactJS application.
- **backend**: Contains the FastAPI application and PostgreSQL database integration.

Each directory has its own README file with detailed instructions specific to that part of the application.

## Getting Started

To get started with this template, please follow the instructions in the respective directories:

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)
The following are the steps to take when running this application locally.

Fork and clone the Repo

Create Dockerfiles

Backend Dockerfile in backend/

Frontend Dockerfile in frontend/

Create docker-compose.yml

Ensure your docker-compose.yml is configured correctly.

Build and Run Containers with docker-compose up --build

Access the Services

Frontend: http://localhost:5173
Backend: http://localhost:8000
Adminer: http://localhost:8080
Nginx Proxy Manager: http://localhost:81
This setup runs the application locally with Docker containers for the frontend, backend, database, and additional services.
