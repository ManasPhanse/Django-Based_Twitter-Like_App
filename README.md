# A Twitter Web like Application using Django Framework (Windows Edition)

## Inspired by
https://realpython.com/django-social-network-1/

## Installation
```
cd C:\Users\...\django-social

py -m venv venv
venv\Scripts\activate
pip install django
```

## How to run development server?

#### Create all the required tables
```
manage.py makemigrations
manage.py migrate
```

## Setup LogIN by
```
python manage.py createsuperuser
```

## LogIN to:
http://127.0.0.1:8000/admin/

## Start Dweets
DashBoard: http://127.0.0.1:8000/

### Modify social/settings.py to run the Web App
```
INSTALLED_APPS = [
    "django.contrib.admin",
    "django.contrib.auth",
    "django.contrib.contenttypes",
    "django.contrib.sessions",
    "django.contrib.messages",
    "django.contrib.staticfiles",
    "dwitter",
]
```

### Run the development server
```
manage.py runserver
```