# Сервис сокращения URL (Short URL)
Создаёт короткие ссылки для длинных URL

## Запуск локально

`uvicorn main:app --reload`

## Запуск в Docker

```
docker build -t url_short .
docker run -p 8000:8000 url_short
```