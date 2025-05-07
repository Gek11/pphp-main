FROM php:7.4-fpm

WORKDIR /var/www/html

RUN docker-php-ext-install mysqli pdo pdo_mysql

COPY . /var/www/html
