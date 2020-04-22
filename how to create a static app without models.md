# how to install pipenv globally on windows?
  - run cmd
  - python --version
  - pip --version
  - pip install pipenv 
  - pipenv --version

# how to create virtual environment?
  - pipenv install django==2.2.4

# how to acticate the virtual environment?
  - pipenv shell

# how to exit virtual environment?
  - exit

# how to make a project in django?
  - django-admin startproject mystaticapp

# how to set up the migrations in django?
  - cd mystaticapp
  - python manage.py migrate

# how to test everything is working in django?
  - python manage.py runserver
  - alt + link to view server
  - ctrl + c to cancel

# how to set up an app in django?
  - python manage.py startapp myapp
  
# what files were changed to achieve this in django?
  - setttings.py update INSTALLED_APPS - 'myapp.apps.MyappConfig'
  - mystaticapp project url
  - newly creatly url for app
  - change in the app views.py
  - create folders inmyapp folder >  myapp/templates/myapp/index.html
  - 