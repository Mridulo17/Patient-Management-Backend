1.Patient-Management-Backend
 Laravel version 9. 
 Composer version 2.7.6
 php": "^8.0.2", 
 Using laravel sanctum for authorization and authentication. 

 composer install

2.In env file 
SANCTUM_STATEFUL_DOMAINS=localhost:3000
SESSION_DOMAIN=localhost

Laravel serve run must be -> php artisan serve --port=8000
