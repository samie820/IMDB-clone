# IMDB-clone

**A side project to develop a clone of the IMDB using django 2.0**

# GETTING STARTED
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

# PREREQUISITES
To setup this project you need to have the following requiremets:
- Django >= 2.0
- PostgreSQL setup locally on your machine
- Docker setup locally on your machine

# INSTALLING

To get started, clone this repository:
`git clone https://github.com/samie820/IMDB-clone.git`

then install all the necessary requirements:
`pip install -r requirements.dev.txt`

then configure django to connect to an already existing postgreSQL DB, go to the `config/settings.py` file:
~~~~
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'mdb', // this should be the database name
        'USER': 'postgres', // the name od the postgres user that the database is created under
        'PASSWORD': '*******', // user's password
        'HOST': '127.0.0.1', //default postgreSQL connection host
        'PORT': '5432' // default port
    }
}
~~~~

# TESTING
Tests will soon be added to this repository

# DEPLOYMENT
This project uses docker for deployment, instructions will soon be added for AWS and heroku

# Built With
- Python 3
- Django 2.**

# AUTHORS
- Omole Samuel [@ajeboDeveloper](https://twitter.com/AjeboDeveloper)
