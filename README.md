Run the Following commands to install Laravel Auth framework in your application.

## Install Laravel Globally in htdocs folder

composer global require laravel/installer

## Create Laravel Project:

laravel new projectName

## Then cd in to the project

cd projectName

## Install Laravel Auth UI

composer require laravel/ui
php artisan ui vue --auth

## Install The NPM

npm install

## Then Start Laravel Project

npm run dev 

## [If Error - Cannot find Webpack]

Then npm update laravel-mix
npm update
npm run dev OR npm run development

## Start Laravel Application

php artisan serve

## For Database Setup [Stop the Server]
Create database in phpmyadmin with the database name given in the .env file.

## Migrate table in your database in phpmyadmin

php artisan migrate

## Reference Video

https://www.youtube.com/watch?v=GjBZOQZsfx8

## Official Documentation

https://laravel.com/docs/9.x/authentication