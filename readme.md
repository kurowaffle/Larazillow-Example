# Larazillow Example

Example project using Laravel, Vue.js, and Inertia.js

## Installing / Getting started

Create database and configure database config in .env. Then execute this:

```shell
> composer install
> npm install
> php artisan migrate:refresh --seed
> php artisan key:generate
> php artisan config:cache
```
## Developing

### Prerequisites
1. Minimum requirement for Laravel 9
3. NPM

### Running Dev

```shell
> php artisan serve
> npm run dev
```
Then open browser and go to `http://localhost:8000`