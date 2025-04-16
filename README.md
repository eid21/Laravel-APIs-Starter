# Laravel APIs

A comprehensive Laravel API project that provides a robust foundation for building RESTful APIs.

## Features

- RESTful API endpoints
- Authentication system
- Database migrations
- API documentation
- Testing suite

## Requirements

- PHP >= 8.1
- Composer
- MySQL
- Node.js & NPM

## Installation

1. Clone the repository
2. Run `composer install`
3. Copy `.env.example` to `.env` and configure your database
4. Run `php artisan migrate`
5. Run `php artisan serve`

## API Documentation

The API documentation is available in Postman format. You can find the collection file at:
```
/postman/Laravel API Starter.postman_collection.json
```

The API includes the following modules:
- User Module (Authentication)
- Products Module
- Orders Module

### Environment Variables
Create a `.env` file in your Postman and add the following variables:
```
url: http://your-api-url
```

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## API COURSE (Project Files)

<img src="https://img-b.udemycdn.com/course/750x422/5201852_fbea_3.jpg">

**Created By :** Mahmoud Anwar
**Email :** Engsahaly@gmail.com

This is the main readme file for the Project files used in the API Course on Udemy

## Installation

To get started, clone this repository.

```
git clone https://github.com/engsahaly/API-COURSE.git
```

Next, copy your `.env.example` file as `.env` and configure your Database connection.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=YOUR-DATABASE-NAME
DB_USERNAME=YOUR-DATABASE-USERNAME
DB_PASSWORD=YOUR-DATABASE-PASSWROD
```

## Run Packages and helpers

You have to all used packages and load helpers as below.

```
composer install
npm install
npm run dev
npm run build
```

## Generate new application key

You have to generate new application key as below.

```
php artisan key:generate
```

## Run Migrations and Seeders

You have to run all the migration files included with the project and also run seeders as below.

```
php artisan migrate
php artisan db:seed
```
#   L a r a v e l - A P I s - S t a r t e r  
 