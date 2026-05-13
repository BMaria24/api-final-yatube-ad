# API для Yatube
API для социальной сети Yatube. Позволяет публиковать посты, комментировать их, подписываться на авторов и работать с группами.

## Установка

1. Клонируйте репозиторий:
```
git clone <url-репозитория>
```
2. Создайте и активируйте виртуальное окружение:
```
python -m venv venv
```

```
venv/Scripts/activate 
```

3.Установите зависимости
```
pip install -r requirements.txt
```

4. Выполните миграции:
```
python manage.py migrate
```

5. Создайте суперпользователя:
```
python manage.py createsuperuser
```

6.Запустите сервер:
```
python manage.py runserver
```