# Django-Mart
Django-Mart is an e-commerce web application built with Django, providing a platform for users to browse products, add items to their cart, and proceed with a secure checkout. The project demonstrates essential e-commerce functionalities like product management, order processing, and user authentication.

## Table of Contents
- Features
- Requirements
- Installation
- Usage
- Project Structure
- Contributing

## Features
- User authentication (sign-up, login, logout)
- Product browsing and search functionality
- Shopping cart with real-time item management
- Order checkout with payment integration (optional)
- Admin panel for product and order management

## Requirements
- Python 3.8+
- Django 3.2+
- Virtualenv (recommended)
- Database (SQLite is default, but PostgreSQL or MySQL can be used)

## Installation
### Clone the Repository:

git clone https://github.com/myself-nahid/Django_Mart.git
cd django-mart

### Create a Virtual Environment:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

### Install Dependencies:
pip install -r requirements.txt

### Apply Migrations:
python manage.py migrate

### Create a Superuser:
python manage.py createsuperuser

### Run the Server:
python manage.py runserver

### Access the Application: 
Open a web browser and go to http://127.0.0.1:8000/.

## Usage
Admin Dashboard: Access the admin panel at http://127.0.0.1:8000/admin to manage products, categories, and orders.
User Registration/Login: Users can create accounts, log in, browse products, and add them to their cart.
Checkout: The cart allows for item adjustments and checkout with payment (if integrated).

## Project Structure
django-mart/
│
├── myapp/                  # Main app folder for models, views, and templates
├── static/                 # Static files (CSS, JavaScript)
├── templates/              # HTML templates
├── db.sqlite3              # SQLite database file (default)
├── manage.py               # Django management script
└── README.md               # Project documentation

## Contributing
- Contributions are welcome! Feel free to open issues, submit pull requests, or suggest new features.