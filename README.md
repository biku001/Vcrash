# Accident Detection Web Application

This is a web application developed using Django to detect car crashes. It uses XAMPP for the server and MySQL for the database management system.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)

## Features
- crash detection
- User authentication and management
- Admin dashboard for monitoring user registrations

## Prerequisites
Before you begin, ensure you have met the following requirements:
- You have installed [XAMPP](https://www.apachefriends.org/index.html).
- You have installed [Python 3.8.10](https://www.python.org/downloads/).
- You have installed [Django](https://www.djangoproject.com/download/).

## Installation

### Step 1: Setting up XAMPP
1. Download and install XAMPP from the [official website](https://www.apachefriends.org/index.html).
2. Start Apache and MySQL from the XAMPP control panel.

### Step 2: Setting up the MySQL Database
1. Open [phpMyAdmin](http://localhost/phpmyadmin).
2. Create a new database called `accident_detection`.
3. Note down the username (`root` by default) and password for the MySQL database.

### Step 3: Setting up the Django Project
1. Clone the repository:
   ```bash
   git clone https://github.com/biku001/Vcrash.git
   cd acc_det
2. Install the required packages
   ```bash
   pip install -r requirements.txt
### Step 4: Apply Migrations and Start the Server
1. Apply database migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
2. Start the Django development server:
   ```bash
   Start the Django development server:


   
