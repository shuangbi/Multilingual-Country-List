# Country Codes for Laravel

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/petercoles/Countries/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/petercoles/Countries/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/petercoles/Countries/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/petercoles/Countries/?branch=master)
[![Build Status](https://travis-ci.org/petercoles/Countries.svg?branch=master)](https://travis-ci.org/petercoles/Countries)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org)

## Introduction

ISO 3166 http://www.iso.org/iso/country_codes

## Installation

At the command line run

```
composer require petercoles/countries
```

then add the service provider to the providers entry in your config/app.php file

```
    'providers' => [
        // ...
        PeterColes\LiveOrLetDie\Providers\CountriesServiceProvider::class,
        // ...
    ],
```

## Usage





## Issues

This package was developed to meet a specific need and then generalised for wider use. If you have a use case not currently met, or see something that appears to not be working correctly, please raise an issue at the [github repo](https://github.com/petercoles/countries/issues)

## License

This package is licensed under the [MIT license](http://opensource.org/licenses/MIT).