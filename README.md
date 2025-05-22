# PC Assignment WebApp

## Prerequisiti
- Docker & Docker Compose

## Avvio
```bash
docker-compose up --build
```
- Backend: http://localhost:5000/api
- Frontend: http://localhost:3000

## Migrazioni DB
```bash
docker-compose exec backend flask db init
docker-compose exec backend flask db migrate
docker-compose exec backend flask db upgrade
```