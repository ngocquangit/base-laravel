## Required enviroiment version

$ php >= 7.0.x

## Installation

``` bash
# install app's dependencies
$ composer install
# generate laravel APP_KEY
$ php artisan key:generate
# run database migration and seed
$ php artisan migrate:refresh --seed
```
## Usage

``` bash
# start local server
$ php artisan serve
# install vue dependencies
$ npm install
# start vue
$ npm run watch