## Introduction

This is a simple Todo application built off Django (including the Django REST Framework for API CRUD operations) and React for frontEnd and SQLite database.

## Requirements
* Python3
* Pipenv --> pip install pipenv

## Getting started
1. Copy the django-todo-react-application  zip to your machine and extract the zip file
2. Navigate into the diretory ```[cd django-todo-react-application]```
3. Source the virtual environment ```[pipenv shell]```
4. Install the dependencies ```[pipenv install]```
5. Install django-cors-headers ```[pip install django-cors-headers]```
6. Install Django-rest-framework ```[pip3 install djangorestframework]```
7. apply database migration ```[python manage.py migrate]```
8. Navigate into the frontend directory ```[cd frontend]```
9. Install the dependencies ```[npm install]```

## Run the application
You will need two terminals pointed to the frontend and backend directories to start the servers for this application.

1. Run this command to start the backend server in the ```[backend]``` directory: ```[python manage.py runserver]``` (You have to run this command while you are sourced into the virtual environment)
2. Run this command to start the frontend development server in the ```[frontend]``` directory: ```[npm start]``` (This will start the frontend on the adddress [localhost:3000](http://localhost:3000))

