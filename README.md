# Django Project

## Описание

Это мой проект для обучения Django. Проект использует файл `.env` для хранения конфигурационных данных.

## Установка

Следуйте инструкциям ниже для установки и запуска проекта локально.

### Шаги установки

1. Клонируйте репозиторий

   ```bash
   git clone https://github.com/jaam8/first_progect_django.git
   cd first_progect_django
   ```

2. Создайте и активируйте виртуальное окружение

3. Установите зависимости

   ```bash
   pip install -r requirements.txt
   ```

5. Настройте файл окружения

   Скопируйте файл `.env.example` в `.env` и отредактируйте его, добавив свои значения.

   ```bash
   cp .env.example .env
   ```

   содержание файла .env
   ```ini
   SECRET_KEY=your_secret_key
   EMAIL_HOST_USER=your_email@gmail.com
   EMAIL_HOST_PASSWORD=your_password
   EMAIL_PORT=port
   ```

7. Примените миграции базы данных

   ```bash
   python manage.py migrate
   ```

8. Запустите сервер разработки

   ```bash
   python manage.py runserver
   ```

## Использование

Откройте браузер и перейдите по адресу [http://127.0.0.1:8000/](http://127.0.0.1:8000/) для доступа к приложению.
