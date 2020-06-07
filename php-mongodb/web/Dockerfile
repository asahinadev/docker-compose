FROM php:7.4.6-fpm

RUN apt-get update  -y 
RUN apt-get install -y libicu-dev
RUN docker-php-ext-configure intl
RUN docker-php-ext-install   intl
RUN docker-php-ext-enable    intl

RUN pecl install mongodb
RUN docker-php-ext-enable mongodb 

# 
WORKDIR /usr/local/src/composer
RUN curl -sS https://getcomposer.org/installer -o composer-setup.php
RUN php composer-setup.php --install-dir=/usr/local/bin/ --filename=composer
RUN chmod +x /usr/local/bin/composer

WORKDIR /var/www/html
