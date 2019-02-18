This is the tutorial from Djangogirls: <https://tutorial.djangogirls.org/en/installation/>

venv name is: djgrlz_blog
project name is: django_blog


TO START a project:
create a virtual environment:
  $ python3 -m venv environment_name

activate virtual env:
  $ source environment_name/bin/activate

ensure latest version of PIP:
  (env_nam)$ python3 -m pip install --upgrade pip

create requirements.txt and add dependencies

install dependencies:
  (env_nam)$ pip install -r requirements.txt

initiate a django project:
  (env_nam)$ django-admin startproject project_name .

For settings changes, see the Djangogirls site <https://tutorial.djangogirls.org/en/django_start_project/>

To set up a sqlite3 database:
  (env_nam)$ python3 manage.py migrate

To start the webserver:
  (env_nam)$ pyhton manage.py runserver

To start building an application:
  python3 manage.py startapp blog
