# Ecommerce Backend

This is a Django-based backend for an Ecommerce application. It provides RESTful APIs for product management, user authentication, and other ecommerce functionalities.

## Project Structure

- `ecommerce_backend/` - Django project folder containing settings, URLs, and WSGI configuration.
- `products/` - Django app handling product-related features.
- `staticfiles/` - Static assets collected here.
- `db.sqlite3` - SQLite database file.
- `manage.py` - Django management script.
- `requirements.txt` - Python dependencies.
- `Procfile` - For deployment with Gunicorn.
- `render.yaml` - Deployment configuration for Render.

## Features

- Product CRUD operations
- User authentication (can be expanded)
- Static file handling
- Deployed with Gunicorn WSGI server

## Installation

1. Clone the repository:
   
   git clone https://github.com/your-username/ecommerce-backend.git
   cd ecommerce-backend
