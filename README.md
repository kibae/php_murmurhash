php_murmurhash
==============

murmurhash 2.0 extension for PHP

## Function
```php
int murmurhash( string $str[, int $seed] )
```

## Install
* tar zxf php_murmurhash.tgz
* cd php_murmurhash
* phpize
* ./configure
* make
* make install
* echo "extension = murmurhash.so" >> /etc/php.ini (your php.ini file)

## Examples
```php
<?php
$str = 'some string';
$hash = murmurhash( $str );
?>
```
