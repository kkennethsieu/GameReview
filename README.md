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

## 📂 Microservice Repositories & Ports

| Service                  | Port  | Repo Link                                              | Description                                              |
|---------------------------|-------|--------------------------------------------------------|----------------------------------------------------------|
| User Service              | 3001  | [https://github.com/kkennethsieu/user-service]((https://github.com/kkennethsieu/User-Service)) | Handles login, signup, and authentication               |
| Game Catalog Service      | 3002  | [https://github.com/kkennethsieu/game-service]((https://github.com/kkennethsieu/Game-Catalog-Service)) | Provides the catalog of games                            |
| Review Service            | 3003  | [https://github.com/kkennethsieu/review-service]((https://github.com/kkennethsieu/Game-Review-Service)) | Stores and retrieves game reviews                        |
| Likes Service             | 3004  | [https://github.com/kkennethsieu/likes-service]((https://github.com/kkennethsieu/CS361-LikesReviewService)) | Tracks likes on reviews                                   |
| Notification Service      | 3005  | [https://github.com/kkennethsieu/notification-service]((https://github.com/kkennethsieu/CS361-NotificationService)) | Sends notifications for review interactions             |
| API Gateway               | 8000  | [https://github.com/kkennethsieu/api-gateway]((https://github.com/kkennethsieu/Game-GatewayAPI))   | Routes requests to the appropriate services             |
| Frontend                  | 5173  | [https://github.com/kkennethsieu/frontend]((https://github.com/kkennethsieu/main_project_frontend))      | React frontend (mock/demo mode for hosted version)      |

---

## 💻 Run Full System Locally

### 1. Clone all repositories into the same folder

Your folder structure should look like this:

```
game-review-platform/
  docker-compose.yml
  user-service/
  game-service/
  review-service/
  likes-service/
  notification-service/
  api-gateway/
  frontend/
```

Clone the repositories:

```
git clone https://github.com/your-username/user-service
git clone https://github.com/your-username/game-service
git clone https://github.com/your-username/review-service
git clone https://github.com/your-username/likes-service
git clone https://github.com/your-username/notification-service
git clone https://github.com/your-username/api-gateway
git clone https://github.com/your-username/frontend
```

---

### 2. Start all services with Docker Compose

```
docker compose up --build
```

- Frontend runs on `http://localhost:5173`  
- Other services run on their respective ports listed in the table above  

---

## 📌 Notes

- Hosted frontend uses **mock/demo data** for login, reviews, likes, and notifications  
- Full system requires **local Docker setup** to see real backend functionality  
- Designed to demonstrate **microservice architecture, Docker orchestration, and full-stack development skills**  

---

## 🎥 Demo Video

(Optional) Include a short demo video showing:

- Login flow  
- Browsing games  
- Posting a review  
- Liking a review  
- Receiving a notification  

[Demo Video Link](#)
