In this DevOps task, you need to build and deploy a full-stack CRUD application using the MEAN stack (MongoDB, Express, Angular 15, and Node.js). The backend will be developed with Node.js and Express to provide REST APIs, connecting to a MongoDB database. The frontend will be an Angular application utilizing HTTPClient for communication.  

The application will manage a collection of tutorials, where each tutorial includes an ID, title, description, and published status. Users will be able to create, retrieve, update, and delete tutorials. Additionally, a search box will allow users to find tutorials by title.

# Project Name
DD Task

## Overview
This repository contains the complete setup for DD Task, including Docker-based deployment, CI/CD automation, and Nginx configuration. The application is fully containerized and can be deployed on any server using Docker Compose.

---

## Repository Contents
- `Dockerfile` : Dockerfile for building the application image.
- `docker-compose.yml` : Orchestrates multiple containers (frontend, backend, database, etc.).
- `.github/workflows/ci-cd.yml` : CI/CD pipeline configuration for automated build, test, and deployment.
- `README.md` : Documentation and setup instructions.
- `nginx/` : Nginx configuration files.
- `src/` : Application source code.

---

## Prerequisites
Make sure you have the following installed:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- Git

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

Run `node server.js`

### Angular Client

cd frontend

npm install

Run `ng serve --port 3000`

You can modify the `src/app/services/tutorial.service.ts` file to adjust how the frontend interacts with the backend.

Navigate to `http://localhost:3000/`

### Screenshots
<img width="1919" height="918" alt="image" src="https://github.com/user-attachments/assets/b673aad0-c3ff-4a00-9ce6-821bfa9d8675" />
<img width="1919" height="950" alt="image" src="https://github.com/user-attachments/assets/27eb132f-9e74-4f3e-bc14-60c996f6b25f" />


