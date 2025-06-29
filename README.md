# lab-homework
# Python + SQLite у Docker

Цей проєкт демонструє запуск Python-скрипта з базою даних SQLite у Docker.

## Вміст

- `app.py` — створює базу `example.db`, таблицю `users`, додає "John Doe", якщо таблиця порожня, та виводить усіх користувачів.
- `Dockerfile` — описує інструкції для запуску в контейнері.

## Запуск

1. Збірка образу:

```bash
docker build -t my-python-app .

2. Запуск контейнера:

```bash
docker run --rm my-python-app
