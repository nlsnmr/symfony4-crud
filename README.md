# Symfony CRUD

### A simple CRUD App With Symfony 4 

__Symfony version__: 4  
__Symfony skeleton__: symfony/skeleton  
__Template engine__: Twig  
__Object Relational Mapper (ORM)__: Doctrine  

![crud](https://monosnap.com/image/n5iplADHj0BjV7uGvYVYCC1Sc0YNUh.png "CRUD App With Symfony 4")

## How to start

``` bash
# Install dependencies
composer install

# Edit the .env file (or create .env.local) and add DB params
php bin/console doctrine:database:create

# Run migrations
php bin/console doctrine:migrations:migrate

# Create host and Check on browser
```
