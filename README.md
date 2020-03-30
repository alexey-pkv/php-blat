# PHP blat
> version 1.0.0

Installation:

```shell script
composer require alexey-pkv/php-blat
```


A php library that adds the **blat** suffix to all php methods.

Usage

```php
var_dump_blat(get_defined_functions_blat());
var_dump_blat(in_array_blat('is_blat_a', get_defined_functions_blat())); 
```