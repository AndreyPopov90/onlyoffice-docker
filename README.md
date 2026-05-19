# ONLYOFFICE Docs + MySQL + NGINX Docker Compose

This project deploys ONLYOFFICE Document Server with MySQL and NGINX using Docker Compose.

## Services

- ONLYOFFICE Document Server
- MySQL 8.0.36
- NGINX 1.24 Alpine

## Requirements

- Docker
- Docker Compose plugin
- Git

## Installation

```bash
git clone https://github.com/AndreyPopov90/onlyoffice-docker.git
cd onlyoffice-docker
cp .env.example .env
nano .env
docker compose up -d
