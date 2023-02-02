# Lab 32 and Lab 33

# Author:
Dylan Cabral

## How to run tests:

`python manage.py` 

runserver Navigate to snacks/tests Run in terminal: `python manage.py test`

## Setup

- `python3.11 -m venv .venv`
- `pip install django `
- `pip install djangorestframework `
- `pip install psycopg2-binary `
- `django-admin startproject snacks_api . `
- `python manage.py startapp snacks` 
- `pip install djangorestframework-simplejwt` 
- `pip install gunicorn` 
- `pip install whitenoise` 
- `python manage.py migrate `
- `pip freeze > requirements.txt` 
- `python manage.py createsuperuser`
- seem to need to create a new super user every time you update django but idk

To run:

`docker compose up`

Load the site at http://0.0.0.0:8000/ or alternatively at http://127.0.0.10:8000/