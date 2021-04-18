# Laravel back-end challenge

Base repository for Laravel back-end coding challenge for applicants.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing
purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* PHP >= 7.3
* BCMath PHP Extension
* Ctype PHP Extension
* Fileinfo PHP Extension
* JSON PHP Extension
* Mbstring PHP Extension
* OpenSSL PHP Extension
* PDO PHP Extension
* PDO_PGSQL PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* Xdebug PHP Extension
* PostgreSQL database
* Composer

### Installing

There are multiple possibilities on getting a development environment up and running. If you prefer to develop in a
Docker environment, it is recommended to use [Laravel Sail](https://laravel.com/docs/8.x/sail). If you prefer a manual
installation, follow the steps below.

#### Manual installation

1. Execute `composer install` to install all composer dependencies.
2. Copy `.env.example` to `.env` and complete the database credentials.
3. Execute `php artisan key:generate`.
4. Execute `php artisan migrate` to create all tables in the database.

For development purposes, it is recommended to serve the application either using
[Laravel Valet](https://laravel.com/docs/8.x/valet) (A linux fork is available) or `php artisan serve`.

## Running the tests

In order to run the tests, the dev dependencies from Composer need to be installed.
This is the default behaviour if you followed the installation instructions above.

* Execute `composer test` to test all PHP files.

## Deployment
n/a

## Authors
* **Marijn van der Horst**

See also the list of [contributors](https://github.com/marketredesign/microservice_dataset/graphs/contributors) who
participated in this project.

## License

This project is licensed under the MRD License - see the [LICENSE](LICENSE) file for details
