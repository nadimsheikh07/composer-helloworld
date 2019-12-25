# composer-helloworld


Installation
============

```
$ composer require nadimsheikh07/hello-composer
```


Usage
=====

The simplest usage of the library would be as follows:
```
<?php

require_once __DIR__ . '/vendor/autoload.php';

use nadimsheikh07\HelloWorld\Index;

$greeting = new Index();

echo $greeting->greet("Hello Composer");

?>
```