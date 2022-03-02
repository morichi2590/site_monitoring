FROM php:7.4.1-fpm

COPY php.ini /usr/local/etc/php/
COPY --from=composer:2 /usr/bin/composer /usr/bin/composer

RUN apt-get update \
  && apt-get install -y git zip unzip vim \
  && docker-php-ext-install bcmath pdo_mysql

WORKDIR /var/www/html