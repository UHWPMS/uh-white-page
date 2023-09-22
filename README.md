# uh-white-page

## Installation

Environment for PHP and Laravel development involves setting up the necessary software and tools to build and run web applications efficiently. Below are the steps to set up a basic environment for PHP and Laravel development.

### Install PHP

- Download and install PHP from the official website: [PHP Downloads](https://www.php.net/downloads.php).

- Make sure to add PHP to your system's PATH so you can run it from the command line.
  
- Replace configuration settings file: php.ini with [php.ini](https://github.com/UHWPMS/uh-white-page/blob/php/php.ini) (Path example:"C:\Program Files\php-8.2.10\php.ini").

### Install Composer

- Composer is a package manager for PHP and is essential for Laravel.
  
- Download and install Composer by following the instructions on the official website: [Composer Downloads](https://getcomposer.org/download/).

Environment for Vue: Ensure you have a local development environment equipped with Node.js and npm (Node Package Manager).

### Install Node.js and npm
- Vue.js requires Node.js, which includes npm (Node Package Manager) for managing packages and dependencies.
  
- Download and install Node.js from the official website: [Node.js Downloads](https://nodejs.org/).

## SetUp

* Clone this repository
* cd uh-white-page folder
* npm install
* npm install vue
* composer install
* cp .env.example .env
* php artisan key:generate
* php artisan config:cache
* php artisan serve
* Click on the link  http://127.0.0.1:8000/



