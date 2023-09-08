# Laravel10RestAPI-WithSanctum

First you make sure created laravel projects last version with composer and connect to your databases before run that step below :

Step-1. run composer require laravel/sanctum

Step-2 run php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"

Step-3 run php artisan migrate

Step-4 run php artisan make:controller Api\\UserController

after run all step below, open UserController and create function and provide code to here for register and login.
