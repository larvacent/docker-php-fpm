ARG PHP_VERSION
FROM larvacent/php:${PHP_VERSION}-fpm-base

LABEL maintainer="support@larvacent.com"

# Add configuration files
COPY image-files /

EXPOSE 9000

CMD ["php-fpm"]