## Kittygram представляет из себя "Instagram" с кошками.  

Он предоставляет следующие возможности: 
  создать, просмотривать, редактировать данные о котах.

проект построен на Django 3.2.3 используется Nginx, Gunicorn

Данный проект использовался для обучения настройки сервера Gunicorn, Nginx
и разворачиванию приложения на сервере

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Intemic/infra_sprint1.git
```

```
cd infra_sprint1
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
