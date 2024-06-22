# This is my package change-user

[![Latest Version on Packagist](https://img.shields.io/packagist/v/rmsramos/change-user.svg?style=flat-square)](https://packagist.org/packages/rmsramos/change-user)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/rmsramos/change-user/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/rmsramos/change-user/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/actions/workflow/status/rmsramos/change-user/fix-php-code-styling.yml?branch=main&label=code%20style&style=flat-square)](https://github.com/rmsramos/change-user/actions?query=workflow%3A"Fix+PHP+code+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/rmsramos/change-user.svg?style=flat-square)](https://packagist.org/packages/rmsramos/change-user)



This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Installation

You can install the package via composer:

```bash
composer require rmsramos/change-user
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="change-user-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="change-user-config"
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="change-user-views"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

```php
$changeUser = new Rmsramos\ChangeUser();
echo $changeUser->echoPhrase('Hello, Rmsramos!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Rômulo Ramos](https://github.com/rmsramos)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
