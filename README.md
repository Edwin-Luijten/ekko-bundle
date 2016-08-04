# Ekko Bundle

[![Latest Version](https://img.shields.io/github/release/edwin-luijten/ekko-bundle.svg?style=flat)](https://github.com/Edwin-Luijten/ekko-bundle/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/Edwin-Luijten/ekko-bundle/master.svg?style=flat-square)](https://travis-ci.org/Edwin-Luijten/ekko-bundle)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/Edwin-Luijten/ekko-bundle.svg?style=flat-square)](https://scrutinizer-ci.com/g/Edwin-Luijten/ekko-bundle/?branch=master)
[![Quality Score](https://img.shields.io/scrutinizer/g/Edwin-Luijten/ekko-bundle.svg?style=flat-square)](https://scrutinizer-ci.com/g/Edwin-Luijten/ekko-bundle/?branch=master)
[![Total Downloads](https://img.shields.io/packagist/dt/edwin-luijten/ekko-bundle.svg?style=flat-square)](https://packagist.org/packages/edwin-luijten/ekko-bundle)

⋅⋅⋅In many modern web applications, web sockets are used to implement real-time, live-updating user interfaces.⋅⋅
⋅⋅⋅When some data is updated on the server, a message is typically sent over a websocket connection to be handled by the client.⋅⋅

⋅⋅⋅This library aims to help you with that, with support for Pusher and Redis.⋅⋅

## Install

Via Composer

``` bash
$ composer require edwin-luijten/ekko-bundle
```

## Usage

Enable the bundle by adding it to the list of registered bundles
in the `app/AppKernel.php` file of your project:

```php
<?php
// app/AppKernel.php

// ...
class AppKernel extends Kernel
{
    public function registerBundles()
    {
        $bundles = array(
            // ...

            new EdwinLuijten\EkkoBundle\EkkoBundle(),
        );

        // ...
    }

    // ...
}
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ ./vendor/bin/phpunit
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email :author_email instead of using the issue tracker.

## Credits

- [Edwin Luijten](https://github.com/Edwin-Luijten)
- [All Contributors](https://github.com/Edwin-Luijten/Ekki/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.