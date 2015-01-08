
Screnshotmachine for PHP
================================

Screenshomachine for PHP is a very small and easy-to-use library for works with https://screenshotmachine.com

Install
-------
via composer

```
php composer.phar require ondrakub/screenshotmachine-php
```

Usage
-----
It is simple to use.

```php
$params = [
		'key' => 'xxxxxx',
		'size' => Screenshotmachine::SIZE_F,
		'url' => 'http://www.kubon.cz',
		'format' => Screenshotmachine::PNG
	];

$sm = new Screenshotmachine($params);

$sm->getScreen();
```

Parameters for constructor you can find in documentation https://screenshotmachine.com/apiguide.php

(c) Ondřej Kubíček, 2015 (http://www.kubon.cz)