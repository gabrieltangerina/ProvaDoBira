FROM php:8.2-apache

RUN apt-get update && \
    apt-get install -y libpq-dev && \
    docker-php-ext-install mysqli pdo_mysql

RUN chown -R www-data:www-data /var/www/html/
RUN chmod -R 755 /var/www/html/