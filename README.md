# Django HTMX Starter

A modern Django starter template with HTMX, Tailwind CSS, and other best practices.

## Features

- Django 5.0
- HTMX for dynamic interactions
- Tailwind CSS for styling
- Whitenoise for static files
- Django Debug Toolbar
- Django REST Framework
- Docker support
- Pre-commit hooks
- Development tools (black, flake8, isort)
- Browser auto-reload

## Getting Started

1. Clone the repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - Unix: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Copy `.env.example` to `.env` and configure
6. Run migrations: `python manage.py migrate`
7. Install Tailwind CSS: `python manage.py tailwind install`
8. Start the development server: `python manage.py runserver`

## Docker

```bash
docker-compose up --build
```

## Development

- Install pre-commit hooks: `pre-commit install`
- Run Tailwind build process: `python manage.py tailwind start`