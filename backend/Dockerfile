FROM php:8.0.3-fpm-buster

RUN docker-php-ext-install bcmath pdo_mysql 

RUN apt update -y --allow-unauthenticated



COPY --from=composer:2.2 /usr/bin/composer /usr/bin/composer


EXPOSE 9000