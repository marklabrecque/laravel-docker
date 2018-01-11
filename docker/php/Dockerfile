# see https://github.com/cmaessen/docker-php-sendmail for more information

FROM php:fpm

RUN apt-get update

RUN docker-php-ext-install mysqli

RUN echo "localhost localhost.localdomain laravel.local" >> /etc/hosts