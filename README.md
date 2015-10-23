# PanaceaApi
The Panacea Mobile PHP class for easy deployment and integration

Panacea Mobile is a communications technology company that provides simplified interfaces to gateways for SMS, USSD and Push.

This library is a copy of the original php class http://www.panaceamobile.com/docs/__examplesource/exsource_e_elite-sms_trunk_web_examples_php_panacea_api.php_b5de023735004d26adc99a37da4721e6.html
written and distributed by Panacea Mobile.

This repo adds support for installation by composer.


## Installation

```bash
composer require superbalist/panaceaapi
```


## Usage

```php
use PanaceaMobile\PanaceaApi;

$gateway = new PanaceaApi();
$gateway->setUsername('[username]');
$gateway->setPassword('[password]');
$gateway->message_send('[to number]', '[message]', '[from number]');
```