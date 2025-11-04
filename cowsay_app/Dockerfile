FROM python:3.9-slim

# Устанавливаем рабочую директорию
WORKDIR /usr/src/app

# Копируем файлы проекта
COPY requirements.txt ./
COPY app.py ./

# Устанавливаем зависимости
RUN pip install --no-cache-dir -r requirements.txt

# Команда запуска приложения
CMD ["python", "./app.py"]
