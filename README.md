# NuSOAP for PHP 5.5 - 7.0

Fork of NuSOAP fixed for PHP 5.5, 5.6 and 7.0 (tested).

All credits belongs to official author(s): http://nusoap.sourceforge.net.

## Usage

```php
// Config
$client = new nusoap_client('example.com/api/v1', 'wsdl');
$client->soap_defencoding = 'UTF-8';
$client->decode_utf8 = FALSE;

// Calls
$result = $client->call($action, $data);
```
