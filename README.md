# Chirper 

Mini Blogging Platform

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation Guide](#installation)

## Prerequisites

Before you begin, ensure you have the following installed:

- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [PHP](https://www.php.net/)
- [Laravel](https://laravel.com/)
- [MySQL](https://www.mysql.com/) (or any other database of your choice)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Shivek-Sharma/chirper.git
    cd chirper
    ```

2. **Install backend dependencies:**

    ```bash
    composer install
    ```

3. **Create a copy of the `.env` file:**

    ```bash
    cp .env.example .env
    ```

    Update the `.env` file with your database credentials.

4. **Generate application key:**

    ```bash
    php artisan key:generate
    ```

5. **Run database migrations:**

    ```bash
    php artisan migrate
    ```

6. **Install frontend dependencies:**

    ```bash
    npm install
    ```

7. **Start the Frontend development server:**

    ```bash
    npm run dev
    ```

8. **Run the Laravel development server:**

    ```bash
    php artisan serve
    ```

    Your application should now be running at [http://localhost:8000](http://localhost:8000).