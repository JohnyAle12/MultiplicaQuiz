<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## About Project

This is a web application where i put some knowledges about laravel framework, here i build a basic api service to list users and them repositories using dependency injection, interfaces, cache, clean code and result paginated.

## Start Project

Before you download project, please run:

```bash
# install vendor packages
$ composer install
```

After configure your .env file according your database enviroment.

For generate the new application key

```bash
# generat new key aplication on the .env file
$ php artisan key:generate
```

You need two environment variables

```bash
CONECTADOS_WEB_API="https://test.conectadosweb.com.co/"
CONECTADOS_WEB_TOKEN="eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9eyJ0ZXN0IjozMjE0MTIsInVzZXIiOiJmM3IyIn0NcPLPRLSvfszQwtxZLyypsm3Y56ELRdppqYXDv2Hagk"
```

After that you can start the application in local with:

```bash
# start the virtual server and run application
$ php artisan serve
```


