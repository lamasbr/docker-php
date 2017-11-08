# Docker PHP images
[![Build Status](https://travis-ci.org/lamasbr/docker-php.svg?branch=master)](https://travis-ci.org/lamasbr/docker-php)

Docker images built on [Chialab PHP 5.6-fpm and 7.1-fpm images](https://hub.docker.com/r/chialab/php/) with the addition of IMAP and LDAP extensions.

## Available tags and `Dockerfile` links
- [`5.6-fpm` (_5.6/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.6/fpm/Dockerfile)
- [`7.1-fpm` (_7.1/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.1/fpm/Dockerfile)

## Installed extensions
The following modules and extensions have been enabled, in addition to those you can already find in the [official PHP image](https://hub.docker.com/r/_/php/):

- `bcmath`
- `bz2`
- `calendar`
- `iconv`
- `imap`
- `intl`
- `gd`
- `ldap`
- `mbstring`
- `mcrypt`
- `memcached`
- `mysql` (_only PHP 5.x_)
- `mysqli`
- `pdo_mysql`
- `pdo_pgsql`
- `pgsql`
- `redis`
- `soap`
- `Zend OPcache` (_PHP 5.5+_)
- `zip`

## Composer
[Composer](https://getcomposer.org) is installed globally in all images. Please, refer to their documentation for usage hints.
