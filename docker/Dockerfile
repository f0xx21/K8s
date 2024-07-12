# Используем базовый образ Python
FROM python:3.9-slim

# Устанавливаем рабочую директорию в контейнере
WORKDIR /app

# Копируем файл app.py в рабочую директорию
COPY app.py .

# Запускаем скрипт
CMD ["python", "app.py"]