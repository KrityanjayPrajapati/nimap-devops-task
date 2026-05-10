# Dockerized FastAPI Application with Jenkins, Prometheus & Grafana

## 👨‍💻 Developed By

**Krityanjay Prajapati**

---

# 📌 Project Overview

This project demonstrates how to:

- Dockerize a FastAPI application
- Persist application data using Docker Volumes
- Run the application using Docker Compose
- Create a Jenkins CI/CD pipeline
- Monitor the application using Prometheus & Grafana

The application stores user data inside a JSON file instead of using a database.

---

# 🚀 Tech Stack

- FastAPI
- Docker
- Docker Compose
- Jenkins
- Prometheus
- Grafana

---

# 📡 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | / | Returns hello message |
| GET | /users | Returns all users |
| POST | /users | Adds user data |
| GET | /metrics | Prometheus metrics |

---

# 📁 Project Structure

```bash
docker-fastapi-test/
│
├── app/
│   └── main.py
│
├── data/
│   └── users.json
│
├── Dockerfile
├── docker-compose.yml
├── Jenkinsfile
├── prometheus.yml
├── requirements.txt
└── README.md
