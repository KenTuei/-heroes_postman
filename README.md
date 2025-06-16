# -heroes_postman
## Hero Powers API (Flask Backend)
This is a simple Flask-based backend API for managing fictional superheroes and their powers. The project includes basic endpoints for retrieving, updating, and assigning powers to heroes using a join model.

## Project Structure
Heroes_Postman
├── app.py          # Main Flask app and routes
├── models.py       # SQLAlchemy models
├── seed.py         # Populates database with sample data
├── migrations/     # Flask-Migrate files
└── app.db          # SQLite database file

## Technologies Used
Python 3.x
Flask
Flask-SQLAlchemy
Flask-Migrate
SQLite

Features
View a list of all heroes

View a single hero and their powers

View all available powers

Edit a power's description

Assign a power to a hero with a specific strength (via a join table)

