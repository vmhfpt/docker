FROM php:8.0.25-fpm

# Install MySQL extension for PHP
RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable pdo_mysql

EXPOSE 9000