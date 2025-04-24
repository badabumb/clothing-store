# Магазин одежды для бренда Silverwax — проект на Flask и MySQL

## Состав проекта

- **Frontend**: HTML/CSS
- **Backend**: Python + Flask
- **База данных**: MySQL + phpMyAdmin
- **Proxy**: nginx
- **Оркестрация**: Docker Compose

## Как запустить

> Требования: установленный [Docker](https://www.docker.com/) и [Docker Compose](https://docs.docker.com/compose/)

1. Клонируй репозиторий или распакуй архив
2. Перейди в директорию с `docker-compose.yml`
3. Запусти сборку и запуск контейнеров:

   ```bash
   docker-compose up --build
   ```
4. Открой в браузере:

   - [http://localhost:5002](http://localhost:8080) — **Frontend**
   - [http://localhost:8080](http://localhost:8081) — **phpMyAdmin**

   **Логин:** `root`  
   **Пароль:** `rootpassword`
