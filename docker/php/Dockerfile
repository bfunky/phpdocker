FROM php:7.1-fpm

ADD https://getcomposer.org/installer /tmp/composer-setup.php

RUN chmod +x /tmp/composer-setup.php

RUN php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer --quiet

RUN rm /tmp/composer-setup.php