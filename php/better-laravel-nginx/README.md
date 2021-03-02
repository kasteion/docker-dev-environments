# It goes something like this:

To create a Laravel project:

> docker run -rm -it --tty -v $PWD:/app composer create-project laravel/laravel src

And next we can execute:

> docker-compose exec php php /var/www/html/artisan migrate

# Better

> docker-compose up -d --build

# We can do something like this with the composer container

> docker-compose run --rm composer require aschmelyun/laravemetrics

# We can do something like this with the npm container

> docker-compose run --rm npm install

# We can do something like this with the artisan container

> docker-compose run --rm artisan migrate
