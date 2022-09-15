# 🐋Docker
----------
создание образа docker:
```
docker build -t serezhs/image_name:v2.11.1989 .
```
создание и запуск контейнера:
```
docker run --name <имя контейнера> <образ, из которого будет запущен контейнер>
```
запустить существующий контейнер:
```
docker container start <CONTAINER ID>
```
остановить запущенный контейнер:
```
docker container stop <CONTAINER ID>
```
удалить контейнер:
```
docker container rm <CONTAINER ID>
```
удалить образ:
```
docker image rm <CONTAINER ID>
```
авторизация пользователя в docker через консоль:
```
docker login
```
загрузить образ на dockerhub:
```
docker push serezhs/image_name:v2.11.1989
```
сборка docker-compose в "фоновом режиме":
```
docker-compose up -d
```
пересборка контейнеров в "фоновом режиме":
```
docker-compose up -d --build
```
выполнение команды внутри контейнера:
```
docker-compose exec web python manage.py migrate
```
удалить все остановленные контейнеры и неиспользуемые образы:
```
docker system prune -a
```
посмотреть все контейнеры docker:
```
docker ps
```

# 🐍VENV (Virtualenv Python)
----------
создать виртуальное окружение:
```
python -m venv venv
```
запустить вертуальное окружение:
```
. venv/Scripts/activate
```
###### или 
```
source venv/scripts/activate
```
обновить pip:
```
python -m pip install --upgrade pip
```
записать все зависимости в файл requirements.txt:
```
pip freeze > requirements.txt
```

# 🔧Django
----------
установка django:
```
django pip install django
```
установка Django REST framework:
```
pip install djangorestframework
```
создание проекта на django:
```
django-admin startproject project_name
```
создание приложения в django:
```
django-admin startapp app_name
```
