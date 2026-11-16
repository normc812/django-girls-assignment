README.md
# Django Girls Tutorial Assignment

This project completes these Django Girls tutorial sections:

- Django installation
- Your first Django Project
- Django Models
- Django admin

## Features

- Blog application with a Post model
- Post author, title, text, and date fields
- Post management through Django admin

## Run locally on Windows

Open a terminal in the project folder and run:

```text
py -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe manage.py migrate
.\.venv\Scripts\python.exe manage.py createsuperuser
.\.venv\Scripts\python.exe manage.py runserver
```

Open http://127.0.0.1:8000/admin/ and sign in.

The local SQLite database is excluded from Git.
Create your own administrator account and sample posts after setup.

This is a classroom development project, not a production deployment.
The fallback Django secret key is for local development only.