# Symfony CRUD

### A simple Symfony 4 CRUD app With Symfony 4

__Template engine__: Twig  
__Object Relational Mapper (ORM)__: Doctrine  

## How to start

``` bash
# Install dependencies
composer install

# Edit the .env file (or create .env.local) and add DB params

# Create Article schema
php bin/console doctrine:migrations:diff

# Run migrations
php bin/console doctrine:migrations:migrate

# Check on browser
```
