<h1 align="center">Rangerz_Template</h1>

<div align="center">
  <p>Magento 2 module template for composer packages in a github repository.</p>
  <img src="https://img.shields.io/badge/magento-2.4-brightgreen.svg?logo=magento&longCache=true" alt="Supported Magento Versions" />
  <a href="https://packagist.org/packages/rangerz/magento2-module-template" target="_blank"><img src="https://img.shields.io/packagist/v/rangerz/magento2-module-template.svg" alt="Latest Stable Version" /></a>
  <a href="https://packagist.org/packages/rangerz/magento2-module-template" target="_blank"><img src="https://img.shields.io/packagist/dt/rangerz/magento2-module-template" alt="Composer Downloads" /></a>
  <a href="https://github.com/rangerz/magento2-module-template/graphs/commit-activity" target="_blank"><img src="https://img.shields.io/badge/maintained%3F-yes-brightgreen.svg" alt="Maintained - Yes" /></a>
  <a href="https://opensource.org/licenses/MIT" target="_blank"><img src="https://img.shields.io/badge/license-MIT-blue.svg" /></a>
</div>

## Prepare `composer.json`

- `composer.json` [example](https://github.com/rangerz/magento2-module-template/blob/master/composer.json)
- `git tag 1.0.0` with same as `"version": "1.0.0"` in `composer.josn`
- Push tag `git push origin 1.0.0 `

## Packagist Setting

- [Create account](https://packagist.org/register/)
- Connect with Github account
- [Submit package](https://packagist.org/packages/submit)
  - URL example: `https://github.com/rangerz/magento2-module-template`

## Badge Setting

- [shields.io](https://shields.io/) - https://github.com/badges/shields

## Installation

```
composer require rangerz/magento2-module-template
bin/magento module:enable Rangerz_Template
bin/magento setup:upgrade
```

## License

[MIT](https://opensource.org/licenses/MIT)
