# Django Blog Project

A simple tweet-style blog application built with Django and Bootstrap.

## Features
- User authentication (register/login/logout)
- Create, edit, delete tweets
- Upload images with tweets
- Responsive Bootstrap UI
- Read-only view for non-logged-in users

## Setup Instructions

### Prerequisites
- Python 3.8+
- Git

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Open http://127.0.0.1:8000 in your browser.

## Deployment

This project can be deployed to platforms like Render, Railway, or Heroku. See deployment guides below.

## Technologies Used
- Django 6.0
- Bootstrap 5
- SQLite (for development)
- Pillow (for image handling)