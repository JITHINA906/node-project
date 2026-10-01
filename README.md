
# Node.js Docker CI/CD Pipeline

## 📌 Project Overview

This project demonstrates a simple Node.js web application with a Docker-based CI/CD pipeline using GitHub Actions.

Whenever changes are pushed to the `main` branch, GitHub Actions automatically:

1. Checks out the source code
2. Sets up Node.js
3. Installs dependencies
4. Runs tests
5. Builds a Docker image
6. Logs in to Docker Hub
7. Pushes the Docker image to Docker Hub

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- Docker
- Docker Hub
- Git
- GitHub
- GitHub Actions

---

## 📁 Project Structure

```text
node-project/
│
├── app.js
├── package.json
├── package-lock.json
├── Dockerfile
├── .dockerignore
├── README.md
│
└── .github/
    └── workflows/
        └── main.yml
