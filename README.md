## AWWWARDS

## Description
Awwards is a platform where users can display their projects for others to see, they can also see other peoples Projects with the languages they have used.
## Author
IKERRIZ

## Set Up and Installations
----------------------------
### Prerequisites
* Ubuntu Software
* Python3.6.8
* Postgres
* python virtualenv
## Clone the Repo
Run the following command on the terminal: git clone https://github.com/IKERRIZ/Awards.git && cd awwards

## Activate virtual environment
Activate virtual environment using python3.6 as default handler

virtualenv -p /usr/bin/python3.6 venv && source venv/bin/activate
## Install dependancies
Install dependancies that will create an environment for the app to run pip3 install -r requirements.txt

## Create the Database
psql
CREATE DATABASE awwards;
## .env file
Create .env file and paste paste the following filling where appropriate:

 * SECRET_KEY = '<Secret_key>'
 * DBNAME = '<database_name>'
 * USER = '<Username>'
 * PASSWORD = '<password>'
 * DEBUG = True

* EMAIL_USE_TLS = True
* EMAIL_HOST = 'smtp.gmail.com'
* EMAIL_PORT = 587
* EMAIL_HOST_USER = '<your-email>'
* EMAIL_HOST_PASSWORD = '<your-password>'

## Run initial Migration
python3.6 manage.py makemigrations insta
python3.6 manage.py migrate
## Run the app
python3.6 manage.py runserver
Open terminal on localhost:8000

## Live site
https://awwards-ikerriz.herokuapp.com/


## Technologies used
- Python 3.6.8
- HTML
- Bootstrap 4
- Heroku
- Postgresql
## Support and contact details
Contact me for further help/support at okothfaith94@gmail.com

## License
Copyright (c) ikerriz