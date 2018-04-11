# Quick Installation Guide

Installing the Symfony Framework 3 using PHP 7 on Ubuntu 16.04 (Xenial Xerus).

## Composer and PHP Installation (as sudo user (root)):
sudo apt-get update

sudo apt-get upgrade -y

sudo apt-get install composer php7.0 php7.0-xml php7.0-mbstring

## New Symfony Project using Composer:
composer create-project symfony/website-skeleton project_name

## Run project:
cd project_name

php -S 127.0.0.1:8000 -t public

## Test in the browser:
localhost:8000

##

If the message 'Your application is now ready.' symfony installation is ok.
