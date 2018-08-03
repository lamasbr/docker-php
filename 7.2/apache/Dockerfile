FROM chialab/php:7.2-apache

RUN \
    apt-get update \
    && apt-get install -y --no-install-recommends cron vim \
    && apt-get install -y --no-install-recommends libc-client-dev libkrb5-dev \
    && docker-php-ext-configure imap --with-imap --with-imap-ssl --with-kerberos \
    && docker-php-ext-install imap \
    && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
