[![Main Kittygram workflow](https://github.com/melalecks/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/melalecks/kittygram_final/actions/workflows/main.yml)

Kittygram - это полнофункциональное веб-приложение для обмена фотографиями и информацией о котиках.

## Функционал

- **Регистрация и аутентификация** пользователей
- **Создание профилей** котиков с фотографиями
- **Административная панель** для управления контентом

## Стек

### Backend
- **Python**
- **Django**
- **Django REST Framework** для API
- **PostgreSQL** - база данных
- **Gunicorn** - WSGI сервер

### Frontend
- **React**

### Infrastructure
- **Docker** для оркестрации
- **Nginx** как proxy
- **GitHub Actions** для CI/CD

## Заполнение .env
### Требуются следующие данные:
- POSTGRES_USER - имя пользователя БД
- POSTGRES_PASSWORD - пароль от БД
- POSTGRES_DB - имя БД
- DB_HOST - имя контейнера БД
- DB_PORT - порт базы данных
- SECRET_KEY - secret key от приложения
- DEBUG - True или False в зависимости от того, находится ли проект в разработке или на проде
- ALLOWED_HOSTS - имя домена и адрес удаленного сервера
