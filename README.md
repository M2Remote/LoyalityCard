<h4 align="center">Loyalty Card For Customers in Magento 2 || Adobe Commerce || Open Source </h4>

<p align="center"><i>Module || External System Integration || porto architecture</i></p>
<p align="center">
  <img src ="https://img.shields.io/badge/magento-2.2.x%20%7C%202.3.x%20%7C%202.4.x-orange.svg?logo=magento&style=for-the-badge" />
  </a>
  <a href="https://packagist.org/packages/m2remote/loyaltycard/stats">
    <a href="https://gitHub.com/LoyaltyCard/StrapDown.js/graphs/commit-activity" target="_blank"><img src="https://img.shields.io/badge/maintained%3F-yes-brightgreen.svg?style=for-the-badge" alt="Maintained - Yes" /></a>
  </a>
  <a href="https://opensource.org/licenses/MIT" target="_blank"><img src="https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge" /></a>
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

## credits

- Alessandro Ronchi

## Acknowledgements

Thank the following people that contribute this work directly or indirectly:

- [Ivan Chepurnyi](https://twitter.com/IvanChepurnyi), for his presentation about [the challenges of architecting Magento 2 customizations](https://www.youtube.com/watch?v=kd40IkIRzuk)
- [James Cowie](https://twitter.com/jcowie), for his presentation about [the future of Testing Magento 2 code](https://www.youtube.com/watch?v=mHFEYGDUQ-k)
- [Fabian Schmengler](https://twitter.com/fschmengler), for his contribution on [making it easier to write tests on Magento](https://github.com/tddwizard).


## License

[MIT License](https://opensource.org/licenses/MIT)

[magento-badge]:https://img.shields.io/badge/magento-2.3.x%20%7C%202.4.x-orange.svg?logo=magento&style=for-the-badge
