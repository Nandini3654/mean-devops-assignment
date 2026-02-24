# DevOps MEAN Stack Deployment Assignment

## 📌 Project Overview
This project demonstrates containerization and CI pipeline setup for a MEAN stack application.

The repository includes:
- Frontend (Angular)
- Backend (Node.js + Express)
- Docker configuration
- GitHub Actions CI pipeline

---

## 1️⃣ Repository Setup
- Created a new GitHub repository.
- Pushed complete frontend and backend code.
- Structured project with separate directories.

---

## 2️⃣ Containerization
- Created Dockerfile for backend.
- Created Dockerfile for frontend.
- Configured docker-compose.yml for multi-container setup.

To build locally:
```bash
docCI Pipeline Configuration

Implemented GitHub Actions workflow.

On every push to main branch:

Backend Docker image builds automatically.

Frontend Docker image builds automatically.

Workflow execution confirmed successful.

 Pending Deployment Steps (Planned Implementation)

The following steps are identified for full production deployment:

Push Docker images to Docker Hub.

Deploy application on Ubuntu VM (AWS/Azure).

Integrate MongoDB container.

Configure Nginx reverse proxy (Port 80).

Implement full CI/CD pipeline for automatic deployment.

🛠 Technologies Used

Docker

Docker Compose

GitHub Actions

Node.js

Angular

 Status

CI pipeline is successfully configured and running.
Containerization completed.
Cloud deployment and reverse proxy setup planned as next phase.ker-compose build
