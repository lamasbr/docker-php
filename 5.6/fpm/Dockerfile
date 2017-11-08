FROM chialab/php:5.6-fpm
MAINTAINER llamas.jf@gmail.com

# Install PHP IMAP and LDAP extensions
RUN \
    apt-get update && \
    apt-get install libldap2-dev libc-client-dev libkrb5-dev -y && \
    rm -rf /var/lib/apt/lists/* && \
    docker-php-ext-configure ldap --with-libdir=lib/x86_64-linux-gnu/ && \
    docker-php-ext-configure imap --with-imap --with-imap-ssl && \
    docker-php-ext-install ldap && \
    docker-php-ext-install imap