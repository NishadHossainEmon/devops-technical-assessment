# DevOps Technical Assessment

## Project Overview

This project demonstrates the deployment of two static websites using Docker, Docker Compose, and Nginx Reverse Proxy.

Each website runs in its own Docker container and is managed through Docker Compose. Nginx is configured as a reverse proxy to provide access to both websites.

---

## Project Structure

```
project/
├── site1/
├── site2/
├── nginx/
│   └── nginx.conf
├── docker-compose.yml
└── README.md
```

---

## Technologies Used

- Ubuntu (WSL)
- Docker
- Docker Compose
- Nginx
- Git & GitHub

---

## Running the Project

Start the project:

```bash
docker compose up -d --build
```

Stop the project:

```bash
docker compose down
```

Check running containers:

```bash
docker ps
```

---

## Access the Websites

- http://localhost:8080/site1
- http://localhost:8080/site2

---

## Repository

GitHub Repository:

**https://github.com/NishadHossainEmon/devops-technical-assessment**
