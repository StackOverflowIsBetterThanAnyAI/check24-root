# Guide

## Frontend

- alle API Calls auf http://localhost:8080 schicken
- next.config.ts: output: 'standalone'
- fetch data: cache: 'no-store'

## Backend

- lokale Entwicklung mit SQLite
- Dockerfile
- docker build -t backend .; docker run -p 8080:8888 backend

- db.php abändern: PostgreSQL
- publish image in GHCR
- push to GitHub

## Frontend

- Dockerfile
- replace localhost call with /api
- publish image in GHCR
- push to GitHub

## Root

- nginx
- docker-compose
- http://localhost:9009
