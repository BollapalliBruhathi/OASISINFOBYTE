# OASISINFOBYTE


              LOGIN AUTHENTICATION

This repository contains a simple web application built with Flask for user login authentication. It utilizes MongoDB for storing user data and login sessions, Flask-Bcrypt for password hashing, and Flask-PyMongo for interacting with the MongoDB database.

Features
User registration: Users can create an account by providing their first name, last name, username, and password.
User login: Registered users can log in using their username and password.
Session management: User sessions are managed using Flask's session functionality.
Password hashing: User passwords are hashed using Flask-Bcrypt before being stored in the database.
MongoDB integration: MongoDB is used as the backend database for storing user data and login sessions.
Installation

Clone the repository:

git clone https://github.com/kavyaballa1020/Oasis-Login-Authentication.git
Navigate to the project directory:

cd flask-login-authentication
Install the dependencies:

pip install -r requirements.txt
Set up environment variables:

Create a .env file in the project root directory.
Define the following variables in the .env file:
SECRET_KEY: A secret key used for session management.
MONGO_URI: URI for connecting to your MongoDB database.
Run the application:

python app.py
Access the application in your web browser at http://localhost:5000.

Usage
Register a new account by clicking on the "Register" link and providing the required information.
Log in using your registered username and password.
Upon successful login, you will be redirected to the secured page displaying your first name and last name.
Click on the "Logout" link to log out of your session
