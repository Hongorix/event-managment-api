# Event Managment API

API that can manage events with CRUD operations, relation loading traits, email notification about events and authorization with Sanctum. Also it has factory and seeders to quickly fill up your DB with new data. Project based on [Laravel](https://laravel.com/) Framework.

To use this API you need to make sure that you have
installed [php8+](https://www.php.net/) and [Composer](https://getcomposer.org/download/). If you use email notifications you also need to set up [Mailpit](https://github.com/axllent/mailpit) and connect it to the project.

# Getting started

1. Clone repository.
2. In project folder run `composer install` commad.
3. Set up new database using `docker-compose up` command, or connect exiting one.
4. Run `cp .env.example .env` command and edit .env file for database connection.
5. Run `php artisan migrate` if you are setting up new DB then run `php artisan migrate:refresh --seed` to fill your database.
6. Run `php artisan serve` to launch API.

# Avaible requests

<img src="https://i.imgur.com/mxCKXXO.png">

## Route-list

<img src="https://i.imgur.com/AKdiSDn.png">
