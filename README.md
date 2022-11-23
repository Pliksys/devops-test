# DevOps JR

## API de ejemplo

Este repositorio tiene una API desarrollada en PHP con el framework de Laravel.

Para que funcione en local necesitas tener instalado PHP 7.4 o superior y composer 2.X

Para poder lanzar la aplicación necesitas ejecutar los siguientes comandos:

```bash

composer install
php artisan migrate --force
php artisan serve --host=0.0.0.0 --port=8000

```

Para probar que funciona la aplicación solamente tienes que abrir tu explorador favorito y navegar a la URL: hott://localhost:8000/api/helloworld y te tiene que presentar por pantalla la cadena 'Hellow World'

Esta aplicación además tiene test integrados que puedes ejecutarlos de la siguiente forma:

```bash

composer install
vendor\bin\phpunit

```

## Reto



