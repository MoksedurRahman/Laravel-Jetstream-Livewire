# Laravel-Jetstream-Livewire
Laravel 8.x Authentication with Jetstream and Livewire - Installation Guide

Installation Via Composer
> composer create-project laravel/laravel Laravel-Jetstream-Livewire

Installing Jetstream
https://jetstream.laravel.com/2.x/installation.html
- composer require laravel/jetstream <br>
- php artisan jetstream:install livewire<br>
- php artisan jetstream:install inertia --teams<br>
- npm install<br>
- npm run dev <br>

Set database name, user name and password name in .env file
- php artisan migrate <br>
- php artisan vendor:publish --tag=jetstream-views <br>
- php artisan serve
