Neobis_auth_project

The "Neobis_auth_project" is a simple system for user registration and web application authentication using the Django framework.

This project allows you to quickly create a web application with user registration and authentication functionality and provides basic protection for routes that require authentication.
Requirements

Before getting started with the project, ensure that the following components are installed on your computer:

    Python (recommended version 3.6 and above)
    Django (install using pip install Django)
    Virtual environment (recommended but optional)

Installation and Running

  Clone the repository: 

    git clone https://git@github.com:AibekYrysbekov/Neobis_auth_project_1.git
    
 Create and activate a virtual environment (optional):

    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate  # For Windows

Install dependencies:

    pip install -r requirements.txt

Apply database migrations:

    python manage.py migrate

Start the Django development server:

     python manage.py runserver

Access the application in your web browser at http://localhost:8000/.

Usage

The project provides the following features:
    
        Registration of new users.
        Authentication of existing users.
        Protection of routes that require authentication.

You can customize and extend the project to meet your specific needs.

Author:
Aibek Yrysbekov
