# laravel-docker


### Usage

1. Pull this project to your machine.

2. docker-compose up -d

3. initialize laravel project:
   - cp .env.example .env
   - docker-compose exec app php artisan key:generate
   - docker-compose exec app php artisan optimize
   - docker-compose exec app php artisan migrate
   - docker-compose exec app php artisan make:auth
   
   Then visit http://127.0.0.1:8080/login you will find everything works like a charm!
