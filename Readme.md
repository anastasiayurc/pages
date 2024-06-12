## Initial set up

- clone this directory and navigate into it 
- create a new virtual environment called .venv and activate it
- install Django
- create a new Django project called django_project
- create a new app called pages

Within a new command line shell start by typing the following:
1. `git clone this repo`
2. `cd pages`
3. `python3 -m venv .venv`
4. `source .venv/bin/activate`
5. `python3 -m pip install django~=4.0.0`
6. `django-admin startproject django_project . `
7. `python3 manage.py startapp pages`

Migrate the database:
1. `python manage.py migrate`
2. `python manage.py runserver`

To run the tests:
`python manage.py test`

To track the changes with Git
1. `git init`
2. `git status`
3. `git add -A`
4. `git commit -m "initial commit"`
5. create a repo in Github and copy its url
6. `git remote add origin https://github.com/anastasiayurc/pages.git`
7. `git push -u origin main`

To ignore the folders that you don't want to track
1. create file `.gitignore` with content `.venv`
