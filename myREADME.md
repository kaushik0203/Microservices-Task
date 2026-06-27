# Microservices Task

## Project Overview

This project demonstrates a Dockerized Node.js microservices architecture consisting of:

- User Service
- Product Service
- Order Service
- API Gateway

The services are containerized using Docker and orchestrated using Docker Compose.

---

## Technologies Used

- Node.js
- Express.js
- Docker
- Docker Compose

---

## Running the Project

```bash
docker compose build
docker compose up
```

---

## API Endpoints

| Service | Endpoint |
|----------|----------|
| Users | http://localhost:3003/api/users |
| Products | http://localhost:3003/api/products |
| Orders | http://localhost:3003/api/orders |

---

## Screenshots

All project screenshots are available in the attached PDF:

**📄 Microservices_Task_Screenshots.pdf**

The PDF includes:

- Project Structure
- Docker Build Output
- Running Containers
- Docker Compose Output
- User API
- Product API
- Create Order API
- Get Orders API
