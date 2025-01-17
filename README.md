# A modern backup solution for Laravel apps

[![Latest Stable Version](https://poser.pugx.org/spatie/laravel-backup/v/stable?format=flat-square)](https://packagist.org/packages/spatie/laravel-backup)
[![MIT Licensed](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/spatie/laravel-backup/run-tests?label=tests)
[![Quality Score](https://img.shields.io/scrutinizer/g/spatie/laravel-backup.svg?style=flat-square)](https://scrutinizer-ci.com/g/spatie/laravel-backup)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/laravel-backup.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-backup)

This Laravel package [creates a backup of your application](https://docs.spatie.be/laravel-backup/v6/taking-backups/overview). The backup is a zip file that contains all files in the directories you specify along with a dump of your database. The backup can be stored on [any of the filesystems you have configured in Laravel 5](http://laravel.com/docs/filesystem).

Feeling paranoid about backups? No problem! You can backup your application to multiple filesystems at once.

Once installed taking a backup of your files and databases is very easy. Just issue this artisan command:

``` bash
php artisan backup:run
```

But we didn't stop there. The package also provides [a backup monitor to check the health of your backups](https://docs.spatie.be/laravel-backup/v6/monitoring-the-health-of-all-backups/overview). You can be [notified via several channels](https://docs.spatie.be/laravel-backup/v6/sending-notifications/overview) when a problem with one of your backups is found.
To avoid using excessive disk space, the package can also [clean up old backups](https://docs.spatie.be/laravel-backup/v6/cleaning-up-old-backups/overview).

## Support us

[![Image](https://github-ads.s3.eu-central-1.amazonaws.com/laravel-backup.jpg)](https://spatie.be/github-ad-click/laravel-backup)

We invest a lot of resources into creating [best in class open source packages](https://spatie.be/open-source). You can support us by [buying one of our paid products](https://spatie.be/open-source/support-us).

We highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using. You'll find our address on [our contact page](https://spatie.be/about-us). We publish all received postcards on [our virtual postcard wall](https://spatie.be/open-source/postcards).

## Installation and usage

This package requires PHP 7.3 and Laravel 5.8 or higher.  
You'll find installation instructions and full documentation on https://docs.spatie.be/laravel-backup.

## Using an older version of PHP / Laravel?

If you are on a PHP version below 7.3 or a Laravel version below 5.8 just use an older version of this package. 

Read the extensive [documentation on version 3](https://docs.spatie.be/laravel-backup/v3), [on version 4](https://docs.spatie.be/laravel-backup/v4) and [on version 5](https://docs.spatie.be/laravel-backup/v5). We won't introduce new features to v5 and below anymore but we will still fix bugs.

## Testing

Run the tests with:

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security-related issues, please email freek@spatie.be instead of using the issue tracker.

## Postcardware

You're free to use this package, but if it makes it to your production environment we highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using.

Our address is: Spatie, Kruikstraat 22, 2018 Antwerp, Belgium.

We publish all received postcards [on our company website](https://spatie.be/en/opensource/postcards).

## Credits

- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
