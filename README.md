# SDPHP Meetup TDD Starter Kit

## Introduction
Starter kit to practice TDD with phpspec & gulp.

Thanks to the [Laracasts katas series](https://laracasts.com/series/code-katas-in-php) for inspiration.

## Prerequisites
* Install PHP 5.6+
* Install Composer (https://getcomposer.org)
* Install Node.js & npm (https://www.npmjs.com/get-npm)
* Install gulp globally (`$ sudo npm install --global gulp-cli`)

The last two are needed only if you want to use the gulp task runner to automatically run unit tests.

## Setup
* Run `$ composer install` to install PHP dependencies.
* Run `$ npm install` to install node dependencies if you want to use the gulp task runner.

## Usage
* Create new spec with `$ bin/phpspec describe FizzBuzz`.
* Run the tests with `$ bin/phpspec run`.
* Run the gulp task runner with `$ gulp`.