# Charriot

## Project Overview

Charriot is a bus ticket booking system where multiple bus owners can register their buses, set destinations, and manage bookings. Users can search for buses based on boarding and destination points, check seat availability, and book tickets seamlessly.

---

### Features

- User Registration & Authentication
- Bus Owner Registration & Management
- Search Buses by Route (Boarding → Destination)
- Seat Availability & Pricing
- Ticket Booking & Cancellation
- Admin Panel for Managing Buses & Users
- Payment Gateway Integration (Future Scope)

### Project Folder Structure

```
Charriot/
│── backend/                  # Backend API
│   │── venv/                 # Virtual environment (don't commit to Git)
│   │── app/                  # Main application package
│   │   │── __init__.py       # Initializes Flask app and extensions
│   │   │── config.py         # Configuration settings
│   │   │── models        	  # Database models (SQLAlchemy)
│   │   │── routes/           # API endpoints
│   │   │   │── __init__.py   # Initializes routes
│   │   │   │── auth.py       # Authentication routes
│   │   │   │── bus.py        # Bus-related routes
│   │   │   │── booking.py    # Booking-related routes
│   │   │── services/         # Business logic and helper functions
│   │   │   │── email_service.py # Email notifications
│   │   │── schemas/          # Request/response validation (if using Marshmallow)
│   │   │── utils/            # Utility functions
│   │   │── extensions.py     # Flask extensions (DB, Migrate, etc.)
│   │   │── errors.py         # Error handling
│   │   │── tasks.py          # Background tasks (if needed)
│   │── migrations/           # Database migration files (Flask-Migrate)
│   │── tests/                # Unit and integration tests
│   │── .env                  # Environment variables (not committed to Git)
│   │── requirements.txt      # Dependencies
│   │── wsgi.py               # Entry point for deployment (Gunicorn, uWSGI)
│
│── frontend/                 # Frontend (if using React/Vue)
│   │── src/                  # Frontend source code
│   │── public/               # Static assets
│   │── package.json          # Dependencies
│   │── index.html            # Main HTML file
│
│── docker/                   # Docker setup (if containerizing)
│── docs/                     # Documentation
│── .gitignore                # Ignore unnecessary files
│── README.md                 # Project overview

```
