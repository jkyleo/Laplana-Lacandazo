# Clinic Patient Records CRUD System

A web-based clinic patient records system developed using Laravel, PHP, MySQL, Blade, and Bootstrap.

## Features

* Register new patients
* View patient records and details
* Search patients by patient number or name
* Edit patient information
* Delete patient records
* Validate patient information
* Display the total number of patients

## Technologies Used

* Laravel
* PHP
* MySQL
* Blade Templates
* Bootstrap 5
* HTML and CSS

## Installation

1. Clone or download this repository.

2. Open the project folder in your terminal.

3. Install PHP dependencies:

   ```bash
   composer install
   ```

4. Create a `.env` file:

   ```bash
   copy .env.example .env
   ```

5. Generate the application key:

   ```bash
   php artisan key:generate
   ```

6. Create a MySQL database named `clinic_crud`.

7. Update the database settings in `.env`.

8. Run the migrations:

   ```bash
   php artisan migrate
   ```

9. Start the development server:

   ```bash
   php artisan serve
   ```

10. Open `http://127.0.0.1:8000` in your browser.

## Developers

* Laplana
* Lacandazo

## Purpose

This project was created as an academic activity for practicing Laravel CRUD operations and database management.
