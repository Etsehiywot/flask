# Flask Tutorial Project

Welcome to the Flask Tutorial Project! This project is designed to help you learn and understand how to build a web application using Flask. It includes features like authentication, templates, and deployment configurations. To get started, clone the repository and follow the steps below.

First, clone the repository:  
`git clone https://github.com/Etsehiywot/flask-tutorial.git`  
`cd flask-tutorial`  

Next, set up a virtual environment:  
`python -m venv venv`  
`venv\Scripts\activate`  

Install the required dependencies:  
`pip install -r requirements.txt`  

Set up the database:  
`flask init-db`  

Run the application:  
`flask run`  

Open your browser and go to `http://127.0.0.1:5000` to access the application.  

The project includes authentication features such as user registration, login, and logout. You can register a new account, log in with your credentials, and log out to end your session. To run the included tests, use the following command:  
`python -m pytest tests\`  

For deployment, follow the configuration in the `setup.py` file. You can deploy the application on platforms like Heroku, Render, or AWS.  

The project structure is organized as follows:  
