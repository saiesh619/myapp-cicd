# myapp-cicd

This repository contains the Jenkins CI/CD pipeline configuration for the **MyApp** project, which is built using **Go (backend)** and **Angular (frontend)**.

---

## Project Overview

The `myapp-cicd` repo automates the building, testing, and deployment of the `MyApp` project using **Jenkins pipelines**. This setup ensures consistent, fast, and reliable integration and delivery of both backend and frontend components.

---

## 🛠️ Tech Stack

- **Backend**: Golang
- **Frontend**: Angular
- **CI/CD Tool**: Jenkins
- **Containerization**: Docker
- **Orchestration/Deployment**: Kubernetes / Docker Compose (customizable)
- **Version Control**: Git (GitHub/GitLab/Bitbucket supported)

---

## 📁 Repository Structure

```plaintext
.
├── Jenkinsfile             # Main Jenkins pipeline definition
├── scripts/
│   ├── build-backend.sh    # Shell script to build Golang backend
│   ├── build-frontend.sh   # Shell script to build Angular frontend
│   └── deploy.sh           # Deployment logic (e.g., Docker/K8s)
├── docker/
│   ├── Dockerfile.backend  # Dockerfile for Golang service
│   └── Dockerfile.frontend # Dockerfile for Angular app
└── README.md
