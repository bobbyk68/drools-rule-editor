# Drools Rule Editor

## Overview
A full-stack rule management UI using:
- Spring Boot + Drools for backend rule processing
- Vue 3 + Vite for frontend rule creation and preview
- Docker + Docker Compose for dev and deployment

## Run Locally
```bash
docker compose up --build
```

Access:
- Frontend: http://localhost:5173
- Backend:  http://localhost:8080/api

## Features
- Sentence-based rule builder UI
- Supports multiple domain objects (e.g. Customer, Invoice)
- JSON versioning for audit/history
- DSL validation and test runner for rule simulation
