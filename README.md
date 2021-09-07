Simple Flask Todo App using SQLAlchemy and SQLite database.

For styling semantic-ui is used.

Setup
Create project with virtual environment

$ mkdir myproject
$ cd myproject
$ python3 -m venv venv
Activate it

$ . venv/bin/activate
or on Windows

venv\Scripts\activate
Install Flask

$ pip install Flask
$ pip install Flask-SQLAlchemy
Set environment variables in terminal

$ export FLASK_APP=app.py
$ export FLASK_ENV=development
or on Windows

$ set FLASK_APP=app.py
$ set FLASK_ENV=development
Run the app

$ flask run
