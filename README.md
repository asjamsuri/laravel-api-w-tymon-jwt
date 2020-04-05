# laravel-api-w-tymon-jwt
This website is intended to demonstrate API Authentication using Tymon JWT as described in [this post](#)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
You need to install composer, XAMPP/WAMP/LAMP/Apache Server if you want to run it locally, and rest client (ex: Postman) to test the API.

## Installing the dependencies
```
composer install
```

## Update database configuration in `.env`
```
DB_DATABASE={database_name}
DB_USERNAME={username}
DB_PASSWORD={password}
```

## Running the database migration
```
php artisan migrate
```

## Genereate keys for token signing
```
php artisan key:generate
```

## Running the application
```
php artisan serve
```

## Dependencies
* [Laravel](https://laravel.com) - The PHP Framework for Web Artisans
* [TymonJWT](https://github.com/tymondesigns/jwt-auth) - JSON Web Token Authentication for Laravel & Lumen