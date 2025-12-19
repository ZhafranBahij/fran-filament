# Fran Filament

## About
Fran Filament is a robust administrative panel built with Laravel Filament v4. It is designed to provide comprehensive user management, role-based access control, and seamless media handling. The project serves as a starting point for building complex administrative interfaces with ease.

## Library
This project leverages the power of the following libraries:
- **Filament Shield** (`bezhansalleh/filament-shield`): For dynamic role and permission management.
- **Filament Export** (`pxlrbt/filament-excel`): To export resource data to Excel.
- **Filament Import** (`eightynine/filament-excel-import`): To import data from Excel files.
- **Spatie Media Library** (`filament/spatie-laravel-media-library-plugin`): For managing user profile photos and other media assets.

## Features
- **Dashboard**: A comprehensive overview with key statistics (e.g., Total Users, Super Admins).
- **User Management**: 
    - Full CRUD (Create, Read, Update, Delete) operations for users.
    - Profile management with photo upload capabilities using Spatie Media Library.
- **Role Management**: Granular control over user roles and permissions.

## How to use

To set up the project locally, follow these steps:

1.  Clone the repository:
    ```bash
    git clone https://github.com/ZhafranBahij/fran-filament.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd fran-filament
    ```
3.  Set up the environment file:
    ```bash
    cp .env.example .env
    ```
4.  Configure the `APP_URL` in `.env` to the URL you use (e.g., `http://localhost:8000`).
5.  Install PHP dependencies:
    ```bash
    composer install
    ```
6.  Run database migrations and seeders:
    ```bash
    php artisan migrate --seed
    ```
7.  Start the development server:
    ```bash
    php artisan serve
    ```
