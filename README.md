<h4 align="center">Loyalty Card For Customers in Magento 2 || Adobe Commerce </h4>

<p align="center"><i>Module || External System Integration || porto architecture</i></p>

<p align="center">
  <a href="https://packagist.org/packages/m2remote/loyaltycard">
    <img src="https://poser.pugx.org/m2remote/loyaltycard/v/stable"
         alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/m2remote/loyaltycard/stats">
    <img src="https://poser.pugx.org/ethanyehuda/magento2-cronjobmanager/downloads"
         alt="Total Downloads">
  </a>
  <a href="https://travis-ci.org/m2remote/loyaltycard">
    <img src="https://travis-ci.org/m2remote/loyaltycard.svg?branch=1.x"
         alt="Travis CI build status">
  </a>
  <a href='https://coveralls.io/github/m2remote/loyaltycard'>
    <img src='https://coveralls.io/repos/github/m2remote/loyaltycard/badge.svg' alt='Coverage Status' />
  </a>
</p>

## Support

CJM Ver. | Magento 2.0 | Magento 2.1 | Magento 2.2 | Magento 2.3 | Magento 2.4
--- | :---: | :---: | :---: | :---: | :---:
1.x | :x: | :x: | ✔️ | ✔️ | ✔️

## Installation

In your Magento2 root directory, you may install this package via composer:

`composer require opensource/loyaltycard`

`php bin/magento setup:upgrade`

## Upgrading the Extension

Composer can be used to upgrade an existing install of the module to the latest release using the following commands:

    composer require opensource/loyaltycard --no-update
    composer update opensource/loyaltycard
    php bin/magento setup:upgrade

## Configuration

## Usage

## Features

## Changelog

## Issue Tracking / Upcoming Features

For issues, please use the [issue tracker](https://github.com/m2remote/loyaltycard/issues).

Issues keep this project alive and strong, so let us know if you find anything!

We're planning on pumping out a ton of new features, which you can follow on our [project page](https://github.com/m2remote/loyaltycard/projects/1).

### Development / Contribution

If you want to contribute please follow the below instructions:

1. Create an issue and describe your idea
2. [Fork this repository](https://github.com/m2remote/loyaltycard/fork)
3. Create your feature branch (`git checkout -b my-new-feature`)
    * **NOTE**: Always branch off the `*-develop` branch (ex. 1.x-develop)
4. Commit your changes
5. Publish the branch (`git push origin my-new-feature`)
6. Submit a new Pull Request for review

## Testing

### Unit Tests

```
./vendor/bin/phpunit tests/unit
```
### Magento Integration Tests

0. Configure test database in `dev/tests/integration/etc/install-config-mysql.php`. [Read more in the Magento docs.](https://devdocs.magento.com/guides/v2.4/test/integration/integration_test_execution.html) 

1. Copy `tests/integration/phpunit.xml.dist` from the package to `dev/tests/integration/phpunit.xml` in your Magento installation.

2. In that directory, run
    ``` bash
    ../../../vendor/bin/phpunit
    ```

## Security

If you discover any security related issues, please email magento2remote@gmail.com instead of using the issue tracker.


## Maintainers

Current maintainers:

* [m2remote](https://github.com/m2remote)
* [Lalit Mohan](https://github.com/lalittmohan)

See also our [contributers](https://github.com/m2remote/loyaltycard/graphs/contributors)


## License

[MIT License](https://opensource.org/licenses/MIT)
