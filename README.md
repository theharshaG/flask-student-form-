# flask-student-form

Flask Student Form (Python Project)
## Overview

This project is a simple web-based Student Form application built using Flask. It allows users to enter their name and age through an HTML form and submit the data to a Flask backend, which processes the input and returns a response.

## Features

HTML form for user input
Form submission using POST method
Flask backend to handle requests
Display user input dynamically
Simple web application structure

## Technologies Used

Python
Flask
HTML
Jinja2 Template Engine

## Project Structure

flask-student-form/
│
├── app.py
├── templates/
│ └── index.html
└── README.md

## How to Run

install python (VS Code)
Install Flask:
pip install flask

Place HTML file inside "templates" folder

Run the program: python app.py

Open browser and go to:
http://127.0.0.1:5000/

## How It Works

The Flask app runs a local server

Home route ("/"):
Loads the HTML form using render_template

User enters name and age in the form

Form sends data to "/submit" route using POST method

Flask receives the data using request.form

The server processes the input and returns a response
Example: Hello Harsha

## Future Improvements

Add form validation
Store data in database
Display submitted data on new page
Add CSS styling
Convert into full student management system
Deploy on cloud platform

## Author
Harsha G
Learning Python | Embedded Systems | IoT
