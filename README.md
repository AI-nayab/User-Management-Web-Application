
# User Management Web Application

## Project Description

The User Management Web Application is a simple full-stack web application developed using Python Flask, HTML, CSS, and SQLite. It allows users to add user details through a web form and display all stored users in a table.

## Technologies Used

* Python
* Flask
* HTML
* CSS
* SQLite

## Project Structure

python-fullstack-task1/

├── app.py

├── database.db

├── templates/

│   └── index.html

└── static/

```
└── style.css
```

## Features

* Add new users
* Store user details in SQLite database
* Display all users in a table
* Simple and clean user interface

## Project Flow

1. User enters Name and Email in the form.
2. The form sends data to the Flask backend.
3. Flask receives the data and stores it in SQLite database.
4. Flask fetches all user records from the database.
5. User records are displayed in an HTML table.

## How to Run

1. Install Flask:
   pip install flask

2. Run the application:
   python app.py

3. Open browser:
   http://127.0.0.1:5000

## Learning Outcome

* Understanding of Flask web framework
* Working with HTML and CSS
* Database connectivity using SQLite
* Full-stack application development basics
