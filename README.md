# Recipe Management API

A production-grade REST API for managing recipes, built with Django & DRF.

## Features

- JWT Authentication
- Full CRUD for Recipes and Users
- Filter by Category or Ingredient
- Search by Title, Category, Ingredients
- Pagination & Sorting
- Deployed on Heroku

## Stack

- Python 3.11, Django 4.2, DRF, PostgreSQL, JWT

## Local Setup

```bash
git clone https://github.com/yourname/recipe_api.git
cd recipe_api
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # fill in values
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## API Base URL

`https://your-app.herokuapp.com/api/v1/`
