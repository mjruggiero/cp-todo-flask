# Full-Stack ToDo Web App using Flask

A To Do List Application written in Python using Flask.

This is a project from the [Clever Programmer](https://www.cleverprogrammer.com/) Profit with Python course.

## Contents

1. [Initial Setup Instructions](#initial-setup-instructions)
1. [Running Server](#running-server)


## Initial Setup Instructions

### Setup Python Virtual Environment
```buildoutcfg
# Create the virtual environment
$ python3 -m venv venv

# Activate the virtual environment
$ . venv/bin/activate

# Install the dependencies
$ pip3 install -r requirements.txt
```

### Creating the database
```buildoutcfg
$ sqlite3 todo.db <---- creates db and runs sqlite3 terminal
sqlite> .tables <---- saves db in sqlite3 terminal
sqlite> .exit <------ closes sqlite3 terminal

$ python / python3 <---- run python terminal
>>> from app import db <----- import db from our flask app inside python terminal
>>> db.create_all() <---- creates tables
>>> exit() <----- exit from terminal
```

## Running Server

```commandline
# Run the server
$ python3 app.py
```
### To view your app, open a web browser to the URL `http://127.0.0.1:5000`
