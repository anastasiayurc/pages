## Initial Set up

• clone this directory and navigate into it 
• create a new virtual environment called .venv and activate it
• install Django
• create a new Django project called django_project
• create a new app called pages

Within a new command line shell start by typing the following:
`git clone this repo
cd pages
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install django~=4.0.0
django-admin startproject django_project .
python3 manage.py startapp pages`

Migrate the database:
`python manage.py migrate`
`python manage.py runserver`

To run the tests:
`python manage.py test`
