FROM php:7.4.6-fpm

RUN apt-get update  -y 
RUN apt-get install -y libicu-dev
RUN docker-php-ext-configure intl
RUN docker-php-ext-install   intl
RUN docker-php-ext-enable    intl
