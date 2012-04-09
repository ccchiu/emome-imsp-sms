emome-imsp-sms 中華電信 emome 簡訊特碼 PHP client library
=====

PHP library for Emome IMSP SMS's HTTP API

## Usage

```php
<?php
Require __DIR__. "/src/EmomeIMSP/SMS.php";
use EmomeIMSP\SMS;

$imsp = new SMS("11582", "6158x");
$response = $imsp->submitSM(
  array("msg"     => "MESSAGE HERE",
        "to_addr" => "MOBILE PHONE NUMBER HERE"
));
var_dump($response);
```
