# 🚀 CRUD DD Task - MEAN Stack DevOps Deployment

## 📌 Project Overview

This project is a full-stack CRUD application built using the MEAN stack:

- MongoDB
- Express.js
- Angular
- Node.js

The application allows users to:
- Create tutorials
- Retrieve tutorials
- Update tutorials
- Delete tutorials
- Search tutorials by title

---

## 🐳 Dockerization

The entire application is containerized using Docker.

Services:
- Frontend (Angular)
- Backend (Node + Express API)
- MongoDB

Docker Compose is used to manage multi-container setup.

To run locally:

```bash
docker-compose up --build
```

---

## ☁️ Deployment

The application is deployed on a cloud VM.

Steps performed:
- Installed Docker & Docker Compose
- Pulled Docker images from Docker Hub
- Deployed containers using docker-compose
- Exposed application on port 80

Application is accessible via public VM IP.

---

## 🔁 CI/CD Pipeline

A GitHub Actions workflow file is included in:

.github/workflows/ci-cd.yml

The pipeline is configured to:
- Trigger on push to main branch
- Build frontend Docker image
- Build backend Docker image

---

## 🐙 Docker Hub Images

Docker images pushed to Docker Hub:

- priyanshu2611/frontend
- priyanshu2611/backend

---

## 📂 Project Structure

```
backend/
frontend/
docker-compose.yml
.github/workflows/
```

---

## ✅ DevOps Tasks Completed

- Application containerization
- Multi-container setup with Docker Compose
- Cloud VM deployment
- Docker Hub integration
- CI/CD workflow configuration
- GitHub repository management

---

## 👨‍💻 Author

Priyanshu Sahu  
GitHub: https://github.com/SahuPrii
