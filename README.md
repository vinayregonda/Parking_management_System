# Parking_management_System
The Django Parking Management System is a web application designed to streamline the management of parking spaces, vehicles, and categories within a parking facility. 

## Introduction

The Django Parking Management System is a web application designed to streamline the management of parking spaces, vehicles, and categories within a parking facility. It provides a user-friendly interface for administrators to monitor parking-related activities, manage vehicle entries and exits, track earnings, and ensure efficient utilization of parking slots.

## Features

### User Authentication and Authorization

- Users can register new accounts or log in with existing credentials.
- Role-based access control ensures that only authorized users can access specific functionalities.

### Dashboard Analytics

- Dashboard provides real-time analytics on key metrics such as:
  - Total parked vehicles
  - Total deported vehicles
  - Total available categories
  - Total earnings
  - Total records
  - Total parking slots

### Vehicle Management

- Add new vehicles to the system with details such as vehicle number, type, parking area, and parking charge.
- Manage the status of vehicles (parked or departed).
- Search for specific vehicles based on criteria like vehicle number, type, or parking area.

### Category Management

- Define and manage different categories of vehicles with attributes like vehicle type, parking area, vehicle limit, and parking charge.
- Activate or deactivate categories based on availability or business requirements.

### Password Reset

- Users can reset their passwords securely through the application.

### Search Functionality

- Search for categories, vehicles, or manage vehicles based on various criteria like parking area, vehicle type, and parking charge.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/vinayregonda/django-parking-management.git

### 2 Navigate to the project directory:
cd django-parking-management

### 3 Install the required dependencies:
pip install -r requirements.txt

## 4 Run migrations to set up the database:
python manage.py migrate

## 5 Start the development server:
python manage.py runserver

*Access the application in your web browser at http://localhost:8000.*

*Usage*

Register a new account or log in with existing credentials.
Explore the dashboard for analytics on parked vehicles, earnings, available categories, and more.
Manage vehicles by adding new ones, changing their status (parked or departed), or searching for specific vehicles.
Manage categories by adding, editing, activating, or deactivating them.
Reset your password if needed.
Use the search functionality to find specific categories, vehicles, or manage vehicles based on various criteria.

*Contributing*
Contributions to this project are welcome! To contribute:

*Fork the repository.*
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -am 'Add new feature').
Push your changes to the branch (git push origin feature-branch).
Create a new Pull Request.

### Contact
For inquiries or support, please contact vinayregonda24@gmail.com.
