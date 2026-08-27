# Laravel and PHP Dockerize

A simple Laravel app running with Nginx, PHP 8.4, and MySQL in Docker.

## Requirements

- Docker
- Docker Compose

## Run

```bash
git clone <repo-url>
cd laravel_and_php_dockerize

docker compose up -d --build
```

Open:

```text
http://localhost:8080
```

## Useful commands

```bash
docker compose ps
docker compose logs -f php
docker compose exec php php artisan migrate
docker compose down
```

## Default database

- Host: mysql
- Database: laravel
- User: laraveluser
- Password: laravelpass

The app is configured in the included `.env` file.
