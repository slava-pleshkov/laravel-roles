<p align="center">
    <a href="https://laravel.com/" target="_blank">
        <img src="https://laravel.com/assets/img/components/logo-laravel.svg" height="100px">
    </a>
    <a href="https://vuejs.org/" target="_blank">
        <img src="https://vuejs.org/images/logo.png" height="100px">
    </a>
    <h1 align="center">laravel-vuejs</h1>
    <br>
</p>
<p align="center">Laravel Framework using Vue.js</p>

## Installation Dev

1. Clone the repo and `cd` into it
1. Create users and table in PostgreSQL
1. Run this command `composer install`
1. Rename or copy `.env.example` file to `.env`
1. Run this command `php artisan key:generate`
1. Set your database credentials in your `.env` file
1. Set your mail credentials in your `.env` file
1. Set your `APP_URL` in your `.env` file
1. Set your `APP_DEBUG` in your `.env` file with the value `true`
1. Run this command `php artisan config:cache`
1. Run this command `php artisan db:seed`
1. Run this command `yarn install`
1. Run this command `yarn run dev`
1. Run this command `php artisan serve` or use Laravel Valet or Laravel Homestead
1. Visit `localhost:8000` in your browser

## Installation Production

1. Clone the repo and `cd` into it
1. Create users and table in PostgreSQL
1. Configure Nginx with these settings `nginx.conf`
1. Run this command `composer install`
1. Rename or copy `.env.example` file to `.env`
1. Run this command `php artisan key:generate`
1. Set your database credentials in your `.env` file
1. Set your mail credentials in your `.env` file
1. Set your `APP_URL` in your `.env` file
1. Set your `APP_DEBUG` in your `.env` file with the value `false`
1. Run this command `php artisan config:cache`
1. Run this command `php artisan db:seed`
1. Run this command `yarn install`
1. Run this command `yarn run production`

## Deploying to Heroku

1. Clone the repo and `cd` into it
1. Run this command `heroku create`
1. Run this command `heroku buildpacks:set heroku/php`
1. Run this command `heroku buildpacks:set heroku/nodejs`
1. Run this command `heroku addons:create heroku-postgresql:hobby-dev`
1. Run this command `heroku config:set APP_NAME=Laravel + Vuejs`
1. Run this command `heroku config:set APP_ENV=production`
1. Run this command `heroku config:set APP_KEY=secret`
1. Run this command `heroku config:set APP_DEBUG=secret`
1. Run this command `heroku config:set TELESCOPE_ENABLED=secret`
1. Run this command `heroku config:set APP_URL=secret`
1. Run this command `heroku config:set LOG_CHANNEL=stack`
1. Run this command `heroku config:set DB_CONNECTION=pgsql`
1. Run this command `heroku config:set DB_HOST=secret`
1. Run this command `heroku config:set DB_PORT=secret`
1. Run this command `heroku config:set DB_DATABASE=secret`
1. Run this command `heroku config:set DB_USERNAME=secret`
1. Run this command `heroku config:set DB_PASSWORD=secret`
1. Run this command `heroku config:set BROADCAST_DRIVER=log`
1. Run this command `heroku config:set CACHE_DRIVER=file`
1. Run this command `heroku config:set SESSION_DRIVER=database`
1. Run this command `heroku config:set SESSION_LIFETIME=120`
1. Run this command `heroku config:set QUEUE_DRIVER=sync`
1. Run this command `heroku config:set MAIL_DRIVER=secret`
1. Run this command `heroku config:set MAIL_HOST=secret`
1. Run this command `heroku config:set MAIL_USERNAME=secret`
1. Run this command `heroku config:set MAIL_PASSWORD=secret`
1. Run this command `heroku config:set MAIL_ENCRYPTION=secret`
1. Run this command `heroku config:set MAIL_FROM_ADDRESS=secret`
1. Run this command `heroku config:set MAIL_FROM_NAME=secret`
1. Run this command `git push heroku master`
1. Run this command `heroku open`

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

