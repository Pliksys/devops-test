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

### Reto 1. Genera un circuito de CI para la aplicación

Debes de usar cualqier motor de CI que conozcas (Github actions por ejemplo) y generar un ciclo de CI coherente

### Reto 2. Dockeriza la aplicación

Crea una imagen de la aplicación y lanza el contenedor probando que funciona como en local

### Reto 3. Dockeriza la Base de datos

En la aplicación la Base de datos que se usa es SqlLite, en este reto buscamos que la cambies por un Base de datos MySql que esté dockerizada

### Reto 4. Orquesta todo con docker-compose

En este reto debes de orquesta la app y su DB a través de un simple docker-compose up

### Reto 5. ¿Cómo desplegarías la aplicación?

Dejamos que vuele tu imaginación para que nos digas cómo desplegarias esta aplicación en tu proveedor cloud favorito