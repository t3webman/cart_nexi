# Cart Nexi

Cart is a small but powerful extension which "solely" adds a shopping cart to your TYPO3 installation.
Cart Nexi is a payment provider and implements the Nexi Easy Payment service.

## 1. Features

- Redirects customer to Nexi for payment.

## 2. Installation

#### Installation using Composer

The recommended way to install the extension is by using [Composer][2]. In your Composer based TYPO3 project root, just do `composer require extcode/cart-nexi`. 

#### Installation as extension from TYPO3 Extension Repository (TER)

Download and install the extension with the extension manager module.

## 3. Administration

## 3.1 Compatibility and supported Versions

| Cart Nexi     | Cart       | TYPO3      | PHP       | Support/Development                     |
| ------------- | ---------- | ---------- | ----------|---------------------------------------- |
| 2.x.x         | 6.3.0      | 9.5        | 7.2       | Features, Bugfixes, Security Updates    |
| 1.x.x         | 5.3.0      | 8.7        | 7.0 - 7.2 | Features _(in certain circumstances with feature toogle)_, Bugfixes, Security Updates    |

### 3.2. Changelog

Please have a look into the [official extension documentation in changelog chapter](https://docs.typo3.org/typo3cms/extensions/cart_nexi/Misc/Changelog/Index.html)

### 3.3. Release Management

News uses **semantic versioning** which basically means for you, that
- **bugfix updates** (e.g. 1.0.0 => 1.0.1) just includes small bugfixes or security relevant stuff without breaking changes.
- **minor updates** (e.g. 1.0.0 => 1.1.0) includes new features and smaller tasks without breaking changes.
- **major updates** (e.g. 1.0.0 => 2.0.0) breaking changes wich can be refactorings, features or bugfixes.

## 4. Sponsoring

*  Ask for an invoice.
*  [Patreon](https://patreon.com/ext_cart)
*  [PayPal.Me](https://paypal.me/extcart)

[1]: https://docs.typo3.org/typo3cms/extensions/cart_events/
[2]: https://getcomposer.org/
