# Funny Inspiring

[![Latest Stable Version](https://poser.pugx.org/gmsantos/inspiring/v/stable)](https://packagist.org/packages/gmsantos/inspiring) [![Total Downloads](https://poser.pugx.org/gmsantos/inspiring/downloads)](https://packagist.org/packages/gmsantos/inspiring) [![Latest Unstable Version](https://poser.pugx.org/gmsantos/inspiring/v/unstable)](https://packagist.org/packages/gmsantos/inspiring) [![License](https://poser.pugx.org/gmsantos/inspiring/license)](https://packagist.org/packages/gmsantos/inspiring) [![Build Status](https://travis-ci.org/gmsantos/inspiring.svg?branch=master)](https://travis-ci.org/gmsantos/inspiring)

Change Laravel inspiring quotes to [Notepad++ easter egg quotes](http://en.wikipedia.org/wiki/Notepad%2B%2B#Easter_egg) and have a lot more inspiration.

## Instalation

Include this package via Composer:

```console
composer require gmsantos/inspiring
```

### Laravel 5.3

In Laravel 5.3, `app/Console/Commands/Inspire.php` has moved to `routes/console.php` clousure command.

Edit your `use` in the same way in Laravel 5.2 and backwards:

```php
<?php

//use Illuminate\Foundation\Inspiring;
use Gmsantos\Inspiring;

/*
|--------------------------------------------------------------------------
| Console Routes
|--------------------------------------------------------------------------
```

### Laravel 5.2 to 5

Edit your `app/Console/Commands/Inspire.php`

```php
<?php

namespace App\Console\Commands;

use Illuminate\Console\Command;
//use Illuminate\Foundation\Inspiring;
use Gmsantos\Inspiring;
```

Then run `php artisan inspire` and have fun! :)
