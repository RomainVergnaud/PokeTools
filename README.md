# PokeTools

## About the project
A Pokédex based PHP web application, inspired by Pokémon universe. 
Will latter incorporate strategic or breeding calculation tools.
Or even a map or infomartion tools on the universe.
It's using [Laravel 5.6](https://laravel.com/docs/5.6) PHP framework.

The url to clone this repository is : *https://github.com/RomainVergnaud/PokeTools.git*.

If you want to edit this file, its original location is : *https://github.com/RomainVergnaud/PokeTools/blob/master/README.md*.

## Table of Contents
1. [About the project](#about-the-projet)
2. [Getting Started](#getting-started)
   * [Requirements](#requirements)
   * [My configuration](#configuration)
   * [Installing](#installing)
   * [Development](#development)
3. [Testing](#testing)
4. [Built With](#built-with)
   * [Laravel packages](#laravel-packages) 
5. [Contributing](#contributing)
6. [Authors](#authors)

## Getting Started
### Requirements
* Apache or Nginx server
* Database server with relationnal DBMS like MySQL or MariaDB
* PHP : 7.1.3+ ([Current releases](http://php.net/downloads.php))
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* Ctype PHP Extension
* JSON PHP Extension
* [Composer](https://getcomposer.org/)
* [Node.js](https://nodejs.org/en/)

### Configuration
This is my personal configuration : 
* Apache HTTPD 2.4.27
* PHP 7.1.16
* MariaDB 10.3.7
* Composer 1.6.5
* Node.js 8.11.2

### Installing
__To install the project you need to :__

1. Clone the distant repository with :
  ```bash
  git clone https://github.com/RomainVergnaud/PokeTools.git
  ```
  
2. Install the composer dependencies :
  ```bash
  composer install
  ```
  
3. Configure your environment by  :
     * Runing : `cp .env.example .env` ;
     * Generate the application key with : `php artisan key:generate` ;
     * Create a new database on your DB Server ;
     * Edit the `APP`, `DB` and `SESSION` environment variables in the `.env` file as you need.
    
### Development
__The development order of the project :__

1. Installing the Laravel Mix environment by running the command :    
     ```bash
     # It will install the Laravel Mix + vueJS Webpack dependencies included in the package.json file.
     npm install
     ```
     
2. To run the Laravel PHP artisan server :
    ```bash
    php artisan serve
    ```
    
3. To compile .scss, .js files and vueJS components, you need to run Laravel Mix tasks with :
    ```bash
    # all Mix tasks, for dev and preproduction
    npm run dev

    #all Mix tasks with minify output for production
    npm run production
    ```
    
    Or you can watch assets changes by running :
    ```bash
    npm run watch
    ```
    If Webpack isn't updating on files change, you can force it :     
    ```bash
    npm run watch-poll
    ```
    
## Testing
Soon update of how to run automated unitary tests for the application. 

## Built With
### Laravel Packages

    
## Contributing
Soon update of contributing rules to this project.

## Authors
- [**Romain Vergnaud**](https://romainvergnaud.fr) / <vergnaud.romain.pro@gmail.com>
