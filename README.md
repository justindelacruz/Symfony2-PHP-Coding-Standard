# Symfony2 PHP CodeSniffer Coding Standard

A code standard to check against the [Symfony coding standards](http://symfony.com/doc/current/contributing/code/standards.html).

Compatible with PHP CodeSniffer 2.x.

## Simple Installation

1. Install phpcs. Follow instructions at [squizlabs/PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer).

2. Clone this repo into the `Standards` directory of PHP CodeSniffer.
 
        cd /path/to/pear/PHP/CodeSniffer/Standards
        git clone https://github.com/justindelacruz/Symfony2-PHP-Coding-Standard.git Symfony2

3. Optionally, set Symfony2 as your default coding standard:

        phpcs --config-set default_standard Symfony2

4. Run `phpcs` and confirm that installation worked:

        cd /path/to/my/project
        phpcs
        phpcs path/to/my/file.php

## Composer Installation

1. Install phpcs. Follow instructions at [squizlabs/PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer).

2. Add this repo as a dependency in `composer.json`:

        composer require --dev justindelacruz/symfony2-php-coding-standard

3. Run `phpcs` using the `standard` parameter, e.g.

        phpcs --standard=./vendor/justindelacruz/symfony2-php-coding-standard/Standards/Symfony2 path/to/my/file.php
