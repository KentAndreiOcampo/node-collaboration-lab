# node-collaboration-lab
A collaborative Node.js lab for 5 team members.

##KonbiniGuard / Conveni
Real-Time Food Freshness & Shelf-Life Management System

#Overview

  KonbiniGuard is a containerized application designed to help convenience stores to track the inventory, monitor the foods freshness in real time, and manage expiration risks to minimize the waste.

  Store use a React-based web dashboard so that they can view live inventory status like ( FRESH, NEAR_EXPIRY, EXPIRED) and can register new batches, An autonomous background worker continuously evaluates products shelf life against database timestamps, automatically updating statuses and logging changes without manual intervention.

#Techology Stack

Frontend: REACT(Vite) for dynamic dashboard with a automatic UI updates for real time item tracking.

Backend: FastAPI with Python 3.12 for high-performance REST endpoints.

Database: PostgreSQL for robust relational data integrity. 

Containerization: Docker & Docker Compose for environment parity.

Testing & CI/CD: Pytest and Jenkins pipeline automation.   

D


## Team Roster
* Maintainer: Kent Ocampo
* QA Lead: Bryan Arcilla
* Developer: James Alavado
* Contributor: Joshua Cevin Calica
* DevOps: Carl Pineda
