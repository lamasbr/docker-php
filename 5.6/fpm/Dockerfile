FROM chialab/php:5.6-fpm
MAINTAINER llamas.jf@gmail.com

# Install PHP IMAP and LDAP extensions
RUN \
    apt-get update && \
    apt-get install libldap2-dev libc-client-dev libkrb5-dev libc-client2007e libc-client2007e-dev -y && \
    rm -rf /var/lib/apt/lists/* && \
	ln -s /usr/lib/libc-client.a /usr/lib/x86_64-linux-gnu/libc-client.a && \
    docker-php-ext-configure ldap --with-libdir=lib/x86_64-linux-gnu/ && \
    docker-php-ext-configure imap --with-imap --with-imap-ssl --with-kerberos --with-libdir=lib/x86_64-linux-gnu/ && \
    docker-php-ext-install ldap && \
    docker-php-ext-install imap