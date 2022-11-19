## laravel-sanctum-api

By Md Naeem Uddin
Software Engineer

### Development environment setup

Used [Laravel](https://laravel.com/docs/9.x) for local development.

## About Project(laravel-sanctum-api)

create laravel simple product crud api with implementation of sanctum package for login and register.

## Tools(laravel-sanctum-api)

-   PHP
-   Laravel Framework
-   MySQL database etc.
-   Laravel sanctum package

#### For a fresh installation of the project:

-   Clone this project:
    `git clone https://github.com/naeemchy/laravel-sanctum-api.git`

-   Copy the `.env` by running this command:
    `cp .env.example .env`

-   Install composer dependencies:
    `composer install`
-   Create an App key by running this command (if you didn't do it already):
    `php artisan key:generate`
-   Then, run:
    `php artisan serve`

The project can now be browsed from here: http://127.0.0.1:8000/

## Database Migration and Seed:

Run following command to prepare the Database:
`php artisan migrate`

or,
import `laravel-sanctum-api.sql` (which are provided in the root directory in this project source code) database in your local machine

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

-   [Simple, fast routing engine](https://laravel.com/docs/routing).
-   [Powerful dependency injection container](https://laravel.com/docs/container).
-   Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
-   Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
-   Database agnostic [schema migrations](https://laravel.com/docs/migrations).
-   [Robust background job processing](https://laravel.com/docs/queues).
-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
