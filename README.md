# Local Authorities Digital Systems Shell to contain all the modules.
## Project Setup
Project was build with laravel 6 and requires PHP 7.3.9 or greater.
Also requires composer to be installed on environment
## How To Run Project

 1. Clone or pull the repository
 2. Run the command below this will install all the required packages for the project: 
 ```
composer install
 ```
 3. Create a .env file using the format specified in the .env-example file.
 4. With your .env file setup specifying the name of the database that you configured run the command below while in the root directory of project. This will run all necessary database migrations for system.
 ```
 php artisan migrate
 ```
 5. Run the command below to generate your app key.
 ```
 php artisan make:key
 ```
6. Your project is now ready to run but needs to seed a default user run the command below to seed
	```
	php artisan db:seed --class=UserRoleSeeder
	```
7. Your project is now ready to run use the command below for dev environment
	```
	php artisan serve
	```
Now can log in with email: blessedmahuni@gmail.com password: eureka 

change this file vendor\laravel\ui\auth-backend\AuthenticatesUsers.php
 
 