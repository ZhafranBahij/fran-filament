# Fran Filament

## About
Fran Filament is a robust administrative panel built with Laravel Filament v4. It is designed to provide comprehensive user management, role-based access control, and seamless media handling. The project serves as a starting point for building complex administrative interfaces with ease.

## Library
This project leverages the power of the following libraries:
- **Filament Shield** ([`bezhansalleh/filament-shield`](https://filamentphp.com/plugins/bezhansalleh-shield)): For dynamic role and permission management.
- **Filament Export** ([`pxlrbt/filament-excel`](https://filamentphp.com/plugins/excel)): To export resource data to Excel.
- **Filament Import** ([`eightynine/filament-excel-import`](https://filamentphp.com/plugins/eightynine-excel-import)): To import data from Excel files.
- **Spatie Media Library** ([`filament/spatie-laravel-media-library-plugin`](https://filamentphp.com/plugins/filament-spatie-media-library)): For managing user profile photos and other media assets.
- **Filament Spatie Health** ([`shuvroroy/filament-spatie-laravel-health`](https://filamentphp.com/plugins/shuvroroy-spatie-laravel-health)): For monitoring the health of the application.
- **Log Viewer** ([`achyutn/filament-log-viewer`](https://filamentphp.com/plugins/achyutn-log-viewer)): For viewing application logs.
- **Filament Laravel Pulse** ([`dotswan/filament-laravel-pulse`](https://filamentphp.com/plugins/dotswan-laravel-pulse)): For comprehensive application monitoring widgets.

## Features
- **Dashboard**: A comprehensive overview with key statistics and monitoring.
    - **Pulse Monitoring**: Real-time insights into servers, cache, exceptions, and usage.
- **User Management**: 
    - Full CRUD (Create, Read, Update, Delete) operations for users.
    - Profile management with photo upload capabilities using Spatie Media Library.
- **Role Management**: Granular control over user roles and permissions.
- **Check Web Health**: Monitor application status, disk usage, and database connectivity.
- **Check Web Log**: View and analyze application logs directly from the dashboard.

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
