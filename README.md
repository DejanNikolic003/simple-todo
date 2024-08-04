# Laravel Todo App

A simple Todo application built with Laravel.

## Features

- User authentication and authorization
- Create, read, update, and delete (CRUD) operations for todos
- Mark todos as complete/incomplete
- Responsive design
- Easy-to-use interface

## Requirements

- PHP >= 8.0
- Composer
- Laravel >= 9.x
- MySQL or SQLite

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/laravel-todo-app.git
    cd laravel-todo-app
    ```

2. Install dependencies:
    ```bash
    composer install
    ```

3. Copy the example environment file and set your environment variables:
    ```bash
    cp .env.example .env
    ```

4. Generate an application key:
    ```bash
    php artisan key:generate
    ```

5. Configure your database settings in the `.env` file:
    ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password
    ```

6. Run the database migrations:
    ```bash
    php artisan migrate
    ```

7. Serve the application:
    ```bash
    php artisan serve
    ```

8. Visit `http://localhost:8000` in your browser to see the app in action.

## Usage

1. Register or log in to your account.
2. Create new todos by clicking on the "Add Todo" button.
3. Manage your todos using the provided interface. You can mark todos as complete, edit them, or delete them.

## Acknowledgments

- [Laravel](https://laravel.com/)
- [Composer](https://getcomposer.org/)
- [Tailwind](https://tailwindcss.com/) for the frontend framework

---

First project in Laravel.
