FROM php:8.0-fpm
RUN apt-get update \
    && docker-php-ext-install pdo pdo_mysql
COPY php.ini /usr/local/etc/php/