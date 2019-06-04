FROM php:7.3-fpm-alpine

WORKDIR /var/www

COPY php.ini $PHP_INI_DIR/conf.d/php.ini

CMD [ "php-fpm" ]

EXPOSE 9000