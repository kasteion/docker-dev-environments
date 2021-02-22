# It goes something like this:

To create a Laravel project:

> docker run -rm -it --tty -v $PWD:/app composer create-project laravel/laravel src

And next we can execute:

> docker-compose exec php php /var/www/html/artisan migrate
