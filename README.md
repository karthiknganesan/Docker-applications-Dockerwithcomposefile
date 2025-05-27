# Docker-applications-Dockerwithcomposefile

Docker Compose Full-Stack Examples

This repository contains Dockerized templates for popular web development stacks using Docker Compose. Each stack includes a Dockerfile and docker-compose.yml to help you get started quickly.

Note: This repository is intended for reference purposes only. It contains only the basic Dockerfile and docker-compose.yml configurations. The actual application source code is not included.

Included Stacks

1. Node.js + MongoDB


2. MERN (MongoDB, Express.js, React.js, Node.js)


3. Angular + Spring Boot + MySQL


4. Laravel + MySQL


5. Django + PostgreSQL


6. Ruby on Rails + PostgreSQL


7. FastAPI + PostgreSQL


8. MEVN (MongoDB, Express.js, Vue.js, Node.js)


9. Flask + Redis


10. Next.js (React Framework) + MongoDB




---

Getting Started

Prerequisites

Docker

Docker Compose


General Usage

Each folder contains an isolated application stack. To run a specific stack:

cd <stack-folder>
docker-compose up --build

Example:

cd nodejs-mongodb
docker-compose up --build

This will build and run all the necessary services (web app, database, etc.) for that stack.


---

Folder Structure

.
├── nodejs-mongodb/
├── mern/
├── angular-springboot-mysql/
├── laravel-mysql/
├── django-postgresql/
├── rails-postgresql/
├── fastapi-postgresql/
├── mevn/
├── flask-redis/
└── nextjs-mongodb/

Each folder contains:

Dockerfile: Instructions to build the app

docker-compose.yml: Multi-container configuration

