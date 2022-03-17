# **Sitemap**

[//]: # ([![License]&#40;https://poser.pugx.org/laravelium/sitemap/license&#41;]&#40;https://packagist.org/packages/laravelium/sitemap&#41; [![PHP tests]&#40;https://github.com/Laravelium/laravel-sitemap/workflows/PHP%20tests/badge.svg?branch=master&#41;]&#40;https://github.com//Laravelium/laravel-sitemap/actions?query=workflow%3A%22PHP+tests%22&#41; [![Maintainability]&#40;https://api.codeclimate.com/v1/badges/c7b8c0079addb1217836/maintainability&#41;]&#40;https://codeclimate.com/github/Laravelium/laravel-sitemap/maintainability&#41; [![Test Coverage]&#40;https://api.codeclimate.com/v1/badges/c7b8c0079addb1217836/test_coverage&#41;]&#40;https://codeclimate.com/github/Laravelium/laravel-sitemap/test_coverage&#41; [![Style Status]&#40;https://github.styleci.io/repos/10392044/shield?style=normal&branch=master&#41;]&#40;https://github.styleci.io/repos/10392044&#41; [![Latest Stable Version]&#40;https://poser.pugx.org/laravelium/sitemap/v/stable&#41;]&#40;https://packagist.org/packages/laravelium/sitemap&#41; [![Total Downloads]&#40;https://poser.pugx.org/laravelium/sitemap/downloads&#41;]&#40;https://packagist.org/packages/laravelium/sitemap&#41;)

Sitemap package for Laravel. forked from laravelium sitemap package.

## Installation

Run the following command and provide the latest stable version (e.g v9.\*) :

```bash
composer require farshidrezaei/sitemap
```

*or add the following to your `composer.json` file :*

#### For Laravel 9
```json
"laravelium/sitemap": "9.*"
```


#### For Laravel 8
```json
"laravelium/sitemap": "8.*"
```

#### For Laravel 7
```json
"laravelium/sitemap": "7.*"
```
(development branch)
```json
"laravelium/sitemap": "7.x-dev"
```

#### For Laravel 6
```json
"laravelium/sitemap": "6.*"
```
(development branch)
```json
"laravelium/sitemap": "6.x-dev"
```

#### For Laravel 5.8
```json
"laravelium/sitemap": "3.1.*"
```
(development branch)
```json
"laravelium/sitemap": "3.1.x-dev"
```

#### For Laravel 5.7
```json
"laravelium/sitemap": "3.0.*"
```
(development branch)
```json
"laravelium/sitemap": "3.0.x-dev"
```

#### For Laravel 5.6
```json
"laravelium/sitemap": "2.8.*"
```
(development branch)
```json
"laravelium/sitemap": "2.8.x-dev"
```

#### For Laravel 5.5
```json
"laravelium/sitemap": "2.7.*"
```
(development branch)
```json
"laravelium/sitemap": "2.7.x-dev"
```

*Publish needed assets (styles, views, config files) :*

```bash
php artisan vendor:publish --provider="Laravelium\Sitemap\SitemapServiceProvider"
```
**Note:** *Composer won't update them after `composer update`, you'll need to do it manually!*

## Examples

- [How to generate dynamic sitemap (with optional caching)](https://github.com/Laravelium/laravel-sitemap/wiki/Dynamic-sitemap)

- [How to generate BIG sitemaps (with more than 1M items)](https://github.com/Laravelium/laravel-sitemap/wiki/Sitemap-index)

- [How to generate sitemap to a file](https://github.com/Laravelium/laravel-sitemap/wiki/Generate-sitemap)

- [How to use multiple sitemaps with sitemap index](https://github.com/Laravelium/laravel-sitemap/wiki/Generate-BIG-sitemaps)

and more in the [Wiki](https://github.com/Laravelium/laravel-sitemap/wiki).

## Contribution guidelines

Before submiting new merge request or creating new issue, please read [contribution guidelines](https://gitlab.com/Laravelium/Sitemap/blob/master/CONTRIBUTING.md).

## License

This package is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).