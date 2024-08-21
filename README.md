# django2.2-python-3.6 video with github.com/codingforentrepreneurs
pipenv --python 3.6 install django==2.2 
pipenv shell
django-admin startproject try_django .
python manage.py runserver
python manage.py migrate
To activate this project's virtualenv, run pipenv shell.
Alternatively, run a command inside the virtualenv with pipenv run.

I am using 3.11 it says 3.6+
to start a project: django-admin startproject try_django .
See the base directory 
from django.conf import settings
>>> settings.BASE_DIR