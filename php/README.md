# Composer

The basic usage of the composer image is

> docker run --rm --interactive --tty --volume $PWD:/app composer (command)

So i can create al laravel project with:

> docker run -rm -it --tty -v $PWD:/app composer create-project laravel/laravel src
