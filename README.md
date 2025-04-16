# Laravel API Project

This project is a RESTful API application built using the Laravel framework.

## Prerequisites

Before you begin, make sure you have the following installed:

- **PHP >= 8.1**
- **Composer**
- **Node.js & NPM**
- **MySQL**

## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/eid21/Laravel-APIs-Starter.git
cd Laravel-APIs-Starter
```

2. **Install PHP dependencies:**
```bash
composer install
```

3. **Install Node dependencies:**
```bash
npm install
```

4. **Copy the environment file:**
```bash
cp .env.example .env
```

5. **Generate the application key:**
```bash
php artisan key:generate
```

6. **Configure your database in `.env`:**
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```

7. **Run the migrations:**
```bash
php artisan migrate
```

8. **Seed the database (optional):**
```bash
php artisan db:seed
```

## Project Structure

- `app/` - Core application logic
- `config/` - Configuration files
- `database/` - Migrations and seeders
- `public/` - Publicly accessible files
- `resources/` - Views and frontend assets
- `routes/` - Route definitions
- `tests/` - Automated tests
- `vendor/` - Composer dependencies

## Running the Application

To start the local development server:
```bash
php artisan serve
```

To run Vite for asset compilation:
```bash
npm run dev
```

## Testing

To execute the test suite:
```bash
php artisan test
```

## Postman Collection

You can find a Postman collection in the `Postman/` directory for testing available API endpoints.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


