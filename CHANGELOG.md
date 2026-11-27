# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 0.2.1 - 2026-11-27
- Added PHP 8.4 and PHP 8.5 support: the `$prefix` parameter of `AbstractValidator::validate()` is now explicitly nullable, which removes the deprecation notice from this package. The `madesimple/php-arrays` 2.x dependency still raises two deprecation notices on PHP 8.4+ (`Arr::column()` and `Arr::pluck()`)
- Added PHP 8.4 and PHP 8.5 to the CI test matrix and quoted the PHP versions, so the `8.0` job runs on PHP 8.0
- Updated the dev dependencies in `composer.lock`, including `phpunit/phpunit` 9.6.39

## 0.2.0 - 2024-03-01
- Added the `min`, `greater-than`, `less-than` validation rules

## 0.1.0 - 2024-02-26

- Created the project with base functionality
- Added the `entity-exists` and `required` validation rules
