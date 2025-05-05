# Build and launch containers
docker-compose up --build

# Stop containers
docker-compose down

## Available Services
Frontend: http://localhost:3000

Backend API: http://localhost:8000

Django Admin: http://localhost:8000/admin

## Technology Stack
Backend: Django 3.1.2 (Python)

Frontend: React 18 (JavaScript)


Containerization: Docker + Docker Compose

Package Management:

pip (Python)

npm (Node.js)

## Project Structure

online_store/
├── frontend/          # React application (Client)
│   ├── public/        # Static assets
│   └── src/           # React components
├── backend/           # Django project (Server)
│   ├── core/          # Main app
│   └── manage.py      # Django management
└── docker-compose.yml # Container orchestration

## First-Time Setup

git@github.com:MaximShamiakov/online_store-fullstac.git
cd online_store-fullstack
git submodule init
git submodule update

# 2. Start services
docker-compose up --build
