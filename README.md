
## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb combination of simplicity, elegance, and innovation give you tools you need to build any application with which you are tasked.

## Server Requirements

 `PHP >= 7.2.5`

## Step to install

composer global require laravel/installer

`Via Composer Create-Project:`
 
 composer create-project --prefer-dist laravel/laravel blog

## Configurations
Application Key
The next thing you should do after installing Laravel is set your application key to a random string. If you installed Laravel via Composer or the Laravel installer, this key has already been set for you by the php artisan key:generate command.

`php artisan key:generate`

## Run server
`php artisan serve`

## Frontend Scaffolding

https://laravel.com/docs/7.x/frontend

composer require laravel/ui

    # Using React
    
    // Generate basic scaffolding...  
    php artisan ui react

    // Generate login / registration scaffolding...
    php artisan ui react --auth