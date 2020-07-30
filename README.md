# Zephir to PHP Converter

[![Downloads total](https://img.shields.io/packagist/dt/migrify/zephir-to-php.svg?style=flat-square)](https://packagist.org/packages/migrify/zephir-to-php/stats)

Convert Zephir (Phalcon custom language) to normal PHP. 
Useful for simple autoloading of static tools like Rector, PHPStan and ECS.

**Before**

```html
@todo
```

**After**

```twig
@todo
```

And much more!

This package won't do it all for you, but **it will help you with 80 % of the boring work**.

## Install

```bash
composer require migrify/zephir-to-php --dev
```

```bash
vendor/bin/zephir-to-php convert /directory
```

<br>

Happy coding!

## Report Issues

In case you are experiencing a bug or want to request a new feature head over to the [migrify monorepo issue tracker](https://github.com/migrify/migrify/issues)

## Contribute

The sources of this package are contained in the migrify monorepo. We welcome contributions for this package on [migrify/migrify](https://github.com/migrify/migrify).
