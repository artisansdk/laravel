# Laravel Application

The starting boilerplate for a Laravel application built with Artisan SDK packages.

## Table of Contents

- [Installation](#installation)
- [Usage Guide](#usage-guide)
- [Running the Tests](#running-the-tests)
- [Licensing](#licensing)

# Installation

The applications installs like any Laravel application:

```bash
git clone git@github.com:artisansdk/laravel ./
composer install
yarn install
npm run dev
cp .env.example .env
php artisan key:generate
```

# Usage Guide

The common use cases for this package should be documented including any troubleshooting.

# Running the Tests

The package is unit tested with 100% line coverage and path coverage. You can
run the tests by simply cloning the source, installing the dependencies, and then
running `./vendor/bin/phpunit`. Additionally included in the developer dependencies
are some Composer scripts which can assist with Code Styling and coverage reporting:

```bash
composer test
composer fix
composer report
```

See the `composer.json` for more details on their execution and reporting output.

# Licensing

Copyright (c) 2019 [Artisans Collaborative](https://artisanscollaborative.com)

This package is released under the MIT license. Please see the LICENSE file
distributed with every copy of the code for commercial licensing terms.