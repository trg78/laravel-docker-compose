
```
Installed:
mariadb  -  composer:1.6  -  adminer   -    php   - laravel
```
```
Download proj.tar, tar -xf proj.tar

docker-compose up --build


Create new db in adminer  - 127.0.0.1:6080   root  123123123     Base -  dka_blog    utf8mb4_unicode_ci   

docker-compose exec web bash
"root@02ca4090e789:/var/www/html#"

php artisan key:generate
php artisan migrate
php artisan key:generate
php artisan config:cache

docker restart (id`s of containers )
If you have some permission problems, try -   
chown -R www-data:www-data /dock/proj/*

```
