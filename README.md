### <p align="center"><b>Welcome to Articly</b></p>
------------

## 🤔 What is Articly?

Articly is a Website Content Management System that will later be able to provide various kinds of educational articles, learning videos and is also expected to be a discussion forum to share knowledge with each other. This website is built with Laravel 9.x Framework

## ⚠️ Requirements needed

- PHP Version 8
- Web Browser (Google Chrome, Firefox, Microsoft Edge)
- Web Server (XAMPP,  Nginx)
- Git Version 2.35.1
- Composer Version 2.2.6
- NodeJS Version 16.14.0 LTS
- Internet Network

## 📕 Installation Guide

1. Repository Clone
```bash
git clone https://github.com/garllockhart/Articly.git
```
```bash
cd Articly
```

2. Install Dependencies
```bash
composer install
```

3. Setup Environment
```bash
cp .env.example .env
```
```bash
php artisan key:generate
```

In order to avoid errors when migrating the database, you must make database settings in the .env file that has been created. Enter the settings like this :
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=YourDatabaseName
DB_USERNAME=YourDatabaseUsername
DB_PASSWORD=YourDatabasePassword
```
```bash
php artisan migrate
```

## 👤 Default Account

Administrator Account
- Username : administrator@articly.com
- Password : 1234567890

User Account
- Username : garllockhart@articly.com
- Password : 1234567890


## 🧑 Developed by <a href="https://www.garllockhart.com">Garly Nugraha</a>

- Instagram <a href="https://www.instagram.com/garllockhart">@garllockhart</a>
- Twitter <a href="https://twitter.com/garllockhart">@garllockhart</a>
- Medium <a href="https://medium.com/@garllockhart">@garllockhart</a>

------------

<p align="center"><b>Made with ❤️ Garly Nugraha & Nazwa Fitriyani Zahra</b></p>
