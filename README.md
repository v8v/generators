Laravel 5 Generators
==============

##Installation##
    composer require "pingpong/generators:~2.1"
    
Next, register new service provider to providers array in config/app.php.

    'Pingpong\Generators\GeneratorsServiceProvider'
    
Done

##Artisan Commands##
In this package, there are many CLI commands that are useful to speed up you in creating web applications with Laravel. Some commands may already be familiar, such as the command to create a controller or model. However we are aware, sometimes we want everything instantly. Although not all of them can be so.
    

##Generate a new controller##
Generate a basic controller.

    php artisan generate:controller UsersController
    
Generate a resource controller.
    
    php artisan generate:controller UsersController --resource
    # OR
    php artisan generate:controller UsersController -r

Generate a scaffolded controller.
    php artisan generate:controller UsersController --scaffold
    # OR
    php artisan generate:controller UsersController -s

##Generate a new model##


##Generate a new console##


##Generate a new form request##
##Generate a new migration##
##Generate a pivot##
##Generate a seed class##
##Generate a view##
##Generate a scaffold resource##
##Modifying Templates##

