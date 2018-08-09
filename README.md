# Docker PHP images
[![Build Status](https://travis-ci.org/lamasbr/docker-php.svg?branch=master)](https://travis-ci.org/lamasbr/docker-php) [![Docker Pulls](https://img.shields.io/docker/pulls/lamasbr/docker-php.svg)](https://hub.docker.com/r/lamasbr/docker-php/) [![Docker Automated build](https://img.shields.io/docker/automated/lamasbr/docker-php.svg)](https://hub.docker.com/r/lamasbr/docker-php/)

Docker images built on [Chialab PHP images](https://hub.docker.com/r/chialab/php/) with the addition of IMAP extension.

## Available tags and `Dockerfile` links
- [`latest` (_/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/Dockerfile)
- [`5.4` (_5.4/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.4/Dockerfile)
- [`5.4-apache` (_5.4/apache/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.4/apache/Dockerfile)
- [`5.4-fpm` (_5.4/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.4/fpm/Dockerfile)
- [`5.5` (_5.5/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.5/Dockerfile)
- [`5.5-apache` (_5.5/apache/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.5/apache/Dockerfile)
- [`5.5-fpm` (_5.5/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.5/fpm/Dockerfile)
- [`5.6` (_5.6/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.6/Dockerfile)
- [`5.6-apache` (_5.6/apache/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.6/apache/Dockerfile)
- [`5.6-fpm` (_5.6/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/5.6/fpm/Dockerfile)
- [`7.0` (_7.0/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.0/Dockerfile)
- [`7.0-apache` (_5.4/apache/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.0/apache/Dockerfile)
- [`7.0-fpm` (_5.4/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.0/fpm/Dockerfile)
- [`7.1` (_7.1/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.1/Dockerfile)
- [`7.1-apache` (_7.1/apache/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.1/apache/Dockerfile)
- [`7.1-fpm` (_7.1/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.1/fpm/Dockerfile)
- [`7.2` (_7.2/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.2/Dockerfile)
- [`7.2-fpm` (_7.2/fpm/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.2/fpm/Dockerfile)
- [`7.2-apache` (_7.2/apache/Dockerfile_)](https://github.com/lamasbr/docker-php/blob/master/7.2/apache/Dockerfile)

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