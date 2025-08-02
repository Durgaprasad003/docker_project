# 🚀 Flask + Docker App

This is a simple Flask web application running inside a Docker container.

---

## 🔧 Project Structure

.
├── app.py # Flask application
├── Dockerfile # Docker setup
└── README.md # Project info


---

## 📦 Requirements

- Python 3.x
- Docker installed

---

## 🐳 How to Run with Docker

### 1️⃣ Build Docker Image

docker build -t flask-docker-app .

## Run the Container
docker run -d -p 5000:5000 flask-docker-app
## Open in Browser
http://localhost:5000
