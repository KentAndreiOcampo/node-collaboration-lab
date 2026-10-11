# node-collaboration-lab
A collaborative Node.js lab for 5 team members.

KonbiniGuard / Conveni
Real-Time Food Freshness & Shelf-Life Management System

Overview

  KonbiniGuard is a containerized application designed to help convenience stores to track the inventory, monitor the foods freshness in real time, and manage expiration risks to minimize the waste.

  Store use a React-based web dashboard so that they can view live inventory status like ( FRESH, NEAR_EXPIRY, EXPIRED) and can register new batches, An autonomous background worker continuously evaluates products shelf life against database timestamps, automatically updating statuses and logging changes without manual intervention.

Techology Stack

Frontend: REACT(Vite) for dynamic dashboard with a automatic UI updates for real time item tracking.

Backend: FastAPI with Python 3.12 for high-performance REST endpoints.

Database: PostgreSQL for robust relational data integrity. 

Containerization: Docker & Docker Compose for environment parity.

Testing & CI/CD: Pytest and Jenkins pipeline automation.   

Getting Started && Local Setup
* Docker Desktop installed and running
* Git
Installation & Run
1. Clone the Respository
Clone the project repository from GitHub and navigate to the project root directory

BASH:
git clone https://github.com/KentAndreiOcampo/node-collaboration-lab.git
cd node-collaboration-lab

2. Configure Environment Variables
Create a local .env configuration file by copying the provided example template

BASH:
cp .env.example .env

ensure the following keys are set inside .env

POSTGRES_DB=konbiniguard
POSTGRES_USER=konbini_admin
POSTGRES_PASSWORD=your_secure_password
DATABASE_URL=postgresql+psycopg2://konbini_admin:your_secure_password@db:5432/konbiniguard

3.Launch Container Stack

BASH:
docker compose up -d --build

4.Access The Interfaces
* Web Dashboard: https:///localhost:8080
* FastAPI Backend Documentation: https://localhost:8000/docs
* PostgreSQL Database Direct Access: localhost:5432

## Team Roster
* Maintainer: Kent Ocampo
* QA Lead: Bryan Arcilla
* Developer: James Alavado
* Contributor: Joshua Cevin Calica
* DevOps: Carl Pineda
