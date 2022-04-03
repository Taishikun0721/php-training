FROM php:8.0-fpm-alpine

WORKDIR /app

COPY ./docker/php/www.conf /usr/local/etc/php-fpm.d/www.conf
COPY . /app
