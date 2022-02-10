# BlogApp


Creating a Blog with Django

1. Create a virtual environment using: 
    -python -m venv venv
2. Activate the virtual environment we just created
    -source venv/bin/activate
3. Install latest django version
    -pip install django

# PROJECT SETUP
4. create a dir
    -mkdir mysite
    $locate to the mysite folder
    -cd mysite
    $create a django project
    -django-admin startproject mysite
- Now your django project structure should look like this 

| — mysite
| | — __init__.py
| | — asgi.py
| | — settings.py
| | — urls.py
| | — wsgi.py
| — manage.py

5. Explaining this files

# __init__.py → A blank Python script which indicates to the Python interpreter that this directory is actually a Python package. It allows Python packages to be imported from the directories.
# asgi.py → Provides a standard interface between async-capable Python web servers, frameworks, and applications.
# settings.py → A file that contains the configuration of the Django project.
# urls.py → A file that contains URL patterns for the Django project.
# wsgi.py → A file that contains WSGI configuration properties of the Django project. It’s basically a Python script that is used to run the development server and to help deploying to a production environment.
# manage.py → A command line utility and allows to interact with the Django project in many ways.

- Now we can execute this command to run the project
    - default run in http://127.0.0.1:8000/
    - python manage.py runserver 8000
