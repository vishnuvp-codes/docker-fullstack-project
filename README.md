# Fullstack Docker Multi-Container Application

This project demonstrates how to run a simple fullstack web application using **Docker** and **Docker Compose**.

The application runs two containers:
- Frontend container
- Backend container

Both containers are managed using Docker Compose.

---

## Project Architecture

Browser
   |
   |---- Frontend Container (Nginx)  -> Port 3000
   |
   |---- Backend Container (Nginx)   -> Port 5000


---

## Project Structure
fullstack-docker-project
│
├── backend
│ ├── Dockerfile
│ └── index.html
│
├── frontend
│ └── Dockerfile
│
├── docker-compose.yml
└── README.md


---

## Technologies Used

- Docker
- Docker Compose
- Nginx
- Linux
