# 🎮 Game Review Microservice Platform

**Full-stack, Dockerized microservice platform for reviewing and liking games.**

---

## 🔹 Project Overview

This platform allows users to:

- Create accounts and log in (User Service)  
- Browse a catalog of games (Game Catalog Service)  
- Post reviews for games (Review Service)  
- Like other users' reviews (Likes Service)  
- Receive notifications when reviews are liked or replied to (Notification Service)  

**Tech Stack:**  
Node.js, Express, React, TailwindCSS, Docker, RabbitMQ, SQLite, Python, Flask

---

## 🌐 Live Demo

- Hosted Frontend (Mock/Data Only): [Vercel Link](https://your-vercel-link.vercel.app)  
- Note: Backend is not hosted. Full system requires local Docker setup.

---

## 📂 Microservice Repositories
| Service                  | Port  | Repo Link                                              | Description                                              |
|---------------------------|-------|--------------------------------------------------------|----------------------------------------------------------|
| User Service              | 3001  | [Repo](https://github.com/your-username/user-service) | Handles login, signup, and authentication               |
| Game Catalog Service      | 3002  | [Repo](https://github.com/your-username/game-service) | Provides the catalog of games                            |
| Review Service            | 3003  | [Repo](https://github.com/your-username/review-service) | Stores and retrieves game reviews                        |
| Likes Service             | 3004  | [Repo](https://github.com/your-username/likes-service) | Tracks likes on reviews                                   |
| Notification Service      | 3005  | [Repo](https://github.com/your-username/notification-service) | Sends notifications for review interactions             |
| API Gateway               | 8000  | [Repo](https://github.com/your-username/api-gateway)   | Routes requests to the appropriate services             |
| Frontend                  | 5173  | [Repo](https://github.com/your-username/frontend)      | React frontend (mock/demo mode for hosted version)      |


## 💻 Run Full System Locally

### 1. Clone all repositories into the same folder including:
```markdown```
  game-review-platform/
  docker-compose.yml
  user-service/
  game-service/
  review-service/
  likes-service/
  notification-service/
  api-gateway/
  frontend/

```bash```
git clone https://github.com/your-username/user-service
git clone https://github.com/your-username/game-service
git clone https://github.com/your-username/review-service
git clone https://github.com/your-username/likes-service
git clone https://github.com/your-username/notification-service
git clone https://github.com/your-username/api-gateway
git clone https://github.com/your-username/frontend

docker compose up --build

```bash```
```markdown```

### 2. Start all services with Docker Compose:


- Frontend runs on http://localhost:5173
- Other services run on their respective ports (configured in Docker Compose)


## 📌 Notes

Hosted frontend uses mock/demo data for login, reviews, likes, and notifications.

Full system requires local Docker setup to see real backend functionality.

Designed to demonstrate microservice architecture, Docker orchestration, and full-stack development skills.
