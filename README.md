# Activate virtual env
. .venv/bin/activate

# use "uv" before pip

# create new django project
django-admin startproject myproject .

python manage.py runserver

# to create app API
python manage.py startapp api

# Install Django, DRF, and MongoEngine
pip install django djangorestframework mongoengine

django-admin startproject config .
python manage.py startapp users

