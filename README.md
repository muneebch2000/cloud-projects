# Project 1 - Dockerized Python Monitoring App

## Overview
A Python Flask web application containerized with Docker and monitored with Prometheus.

## Tech Stack
- Python 3.11
- Flask
- Docker & Docker Compose
- Prometheus

## Project Structure
project1-docker-monitor/
├── app/
│   └── app.py
├── prometheus/
│   └── prometheus.yml
├── Dockerfile
├── docker-compose.yml
└── requirements.txt

## Features
- REST API with health check endpoint
- Prometheus metrics endpoint
- Multi-stage Docker build
- Multi-container setup with Docker Compose

## How to Run
git clone https://github.com/muneebch2000/project1-docker-monitor
cd project1-docker-monitor
docker compose up --build

## Endpoints
| Endpoint | Description |
|----------|-------------|
| / | Main app |
| /health | Health check |
| /metrics | Prometheus metrics |

## Monitoring
- Prometheus Dashboard: http://localhost:9090
- Flask App: http://localhost:5001

## Skills Demonstrated
- Docker containerization
- Multi-stage Dockerfile
- Docker Compose
- Prometheus monitoring
- Python Flask REST API
