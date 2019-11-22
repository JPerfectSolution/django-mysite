MySite-Django

# Setting up a development environment
For ubuntu, you have to install mediainfo package
```
sudo apt-get update
sudo apt-get install mediainfo
```

For local development, first create virtualenv

virtualenv venv
source venv/bin/activate
pip install -r requirements.txt

pytho

# How to run server and Admin on localserver

python manage.py runserver

Admin:=> http://127.0.0.1:8000/

API  :=> http://127.0.0.1:8000/api/v1

# DB Migration

- create user

python manage.py createsuperuser

- model change and migrate to db

python manage.py makemigrations

python manage.py migrate

