# Docker Compose Multi Service Project

This project demonstrates a simple DevOps architecture using Docker Compose.

Stack:
- Python HTTP server
- Nginx reverse proxy
- Docker Compose

Architecture:

Browser → Nginx → Python container

How to run:

docker compose up --build

Open in browser:

http://localhost:8083
