# FlaskApp

Simple application with authentication and CRUD functionality using the Python Flask micro-framework

## Installation

To use this template, your computer needs:

- [Python 2 or 3](https://python.org)
- [Pip Package Manager](https://pypi.python.org/pypi)

## Install dependencies

Install dependencies with below commands:

- pip install flask 
- pip install flask-mysqldb
- pip install flask-WTF
- pip install passlib

## MySQL Commands
- create database myflaskapp;
- use myflaskapp;
- create table users(id INT(10) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(50), email VARCHAR(100), username VARCHAR(30), password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);

- CREATE USER 'appuser'@'localhost' IDENTIFIED BY 'flapass';
- GRANT ALL PRIVILEGES ON users.* TO 'appuser'@'localhost';
- 
## Configure app.py
- Edit app.py and add the MySQL credentials created above.

### Running the app

```bash
python app.py
```

