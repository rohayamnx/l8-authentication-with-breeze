<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/rohayamnx/l8-authentication-with-breeze/refs/heads/main/public/laravel-auth.svg" width="400" alt="Logo">
    </a>
</p>

## Laravel 8 Authentication

A simple authentication page using Laravel 8

## Getting Started

### Clone the Repository

```sh
git clone https://github.com/rohayamnx/l8-authentication-with-breeze.git
```

### Navigate to the Project

```sh
cd l8-authentication-with-breeze
```

### Install Dependencies

```sh
composer install
```

### Copy the Example Environment File

```sh
cp .env.example .env
```

### Generate Application Key

```sh
php artisan key:generate
```

## Configuration
Update the .env file with your database credentials.

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=YOUR_DATABASE_NAME
DB_USERNAME=YOUR_USERNAME
DB_PASSWORD=YOUR_PASSWORD
```

### Run Migrations and Seed the Database

```sh
php artisan migrate
```

```sh
php artisan db:seed UserSeeder
```
### Run the Development Server

```sh
php artisan serve
```

### 5. Open your browser and navigate to

```sh
http://localhost:8000
```