FROM php:8.4-cli

# Install PHPUnit
RUN curl -sS https://phar.phpunit.de/phpunit-9.phar -o /usr/local/bin/phpunit \
    && chmod +x /usr/local/bin/phpunit

WORKDIR /app

ENTRYPOINT ["phpunit"]
