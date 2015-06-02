# This is a forked version of W3 Total Cache

This version support MemcachedSASL with hhvm and use default config from heroku + memcachier addon

## Depedencies

You need to add to your composer.json a requirement on
* "memcachier/php-memcache-sasl": ">=1.0.1"

And ensure to autoload this namesapce in your project

```php
<?php

require_once __DIR__ . '/../vendor/autoload.php';
```
