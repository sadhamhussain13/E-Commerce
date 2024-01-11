# E-commerce Website

This is an e-commerce website built using Python, Django, Bootstrap, and MySQL.

# Table of Content:
1. Project Overview
2. Features
3. Technologies Used
4. Prerequisites
5. Installation and Setup
6. Usage

## Project Overview
This project is a fully functional e-commerce website that allows users to browse products, add items to their cart, and complete the checkout process. The backend is powered by Python Django, while Bootstrap is used for the frontend design. MySQL is used as the database management system.

## Features
- User authentication (registration, login, logout)
- Product listing and categorization
- Customer views cart
- Customer checks out
- Customer sends order
- Shopping cart management
- Database management using MySQL

## Technologies Used
- Python Django: A high-level Python web framework for rapid development and clean, pragmatic design.
- Bootstrap: An open-source CSS framework for building responsive and mobile-first front-end web development.
- MySQL: An open-source relational database management system.

## Prerequisites
- Virtual Environment: Python virtual environment (e.g., venv, pyenv)
- Python: Python 3.X (Recommended: Latest stable version)
- Django: Django framework (Recommended: Latest stable version)
- MySQL: MySQL database server (e.g., MySQL Workbench, XAMPP)
- Bootstrap: Bootstrap library (Included in the project)

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
- `git clone https://your-repository-url.git`
2. Set up a virtual environment:
- Windows: `pip install pipenv`
3. Activate the virtual environment:
- `pipenv --venv`
4. Install project dependencies:
- `pip install <Package-name>`
5. Configure database settings:
- Edit `settings.py` and update database parameters (host, user, password, database name).
6. Migrate database models:
- `python manage.py migrate`
7. Create a superuser account:
- `python manage.py createsuperuser`
8. Run the development server:
- `python manage.py runserver`

## Usage
- Access the website at http://localhost:8000.
- Login with your superuser credentials to access the admin panel: http://localhost:8000/admin
- Manage products, categories, orders, users, and other settings through the admin interface.
- Explore the website as a regular user, add products to the cart, checkout, and experience the full functionality.
   
