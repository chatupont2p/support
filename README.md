# Support config (_cfg) Service Provider for Laravel 5/6/7 

## Installation

The AWS Service Provider can be installed via [Composer](http://getcomposer.org) by requiring the
`chatupont2p/t2p-support` package in your project's `composer.json`.

Usage
-----

### Recommended installation via composer:

Add t2p support to `composer.json` either by running `composer require chatupont2p/t2p-support` or by defining it manually:

    "require": {
       "chatupont2p/t2p-support": "dev-master"
    }

Reinstall dependencies: `composer install`

To use the T2P config Provider, you must register the provider when bootstrapping your application.

### Steps
1. Clone repository and cd into it: `git clone git@github.com:chatupont2p/t2p-support && cd t2p-support`
2. Install dependencies: `composer install`
3. Run unit-tests: `vendor/bin/phpunit`
4. Check PSR compatibility: `vendor/bin/phpcs --standard=PSR2 src tests examples`
