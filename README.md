jQuery Module for PPI2
======================

[@php]: http://php.net/ "PHP: Hypertext Preprocessor"
[@ppi]: http://ppi.io/  "The PPI Framework - A meta-framework built using Symfony2/ZendFramework2 and Doctrine2"
[@jquery]: http://jquery.com/ "jQuery: The Write Less, Do More, JavaScript Library"

This module brings the [jQuery][@jquery] JavaScript library into your [PPI][@ppi] applications.

[![Build Status](https://secure.travis-ci.org/ppi/jquery-module.png)](http://travis-ci.org/ppi/jquery-module)

Requirements
------------

* [PHP][@php] 5.3.3 and up
* [PPI Framework 2][@ppi] (2.1.x)

Installation (Composer)
-----------------------

### 0. Install Composer

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

``` bash
curl -s http://getcomposer.org/installer | php
```

### 1. Add this package to your composer.json

```js
{
    "require": {
        "ppi/jquery-module": "dev-master"
    }
}
```

Now tell composer to download the module by running the command:

``` bash
$ php composer.phar update ppi/jquery-module
```

Composer will install the module to your project's `vendor/ppi` directory.

### 2. Enable the module

Enable this module by editing `app/config/modules.php`:

``` php
<?php
return array(
    'modules' => array(
        // ...
        'PPIJqueryModule',
    ),
    // ...
);
```

License
-------

This bundle is licensed under the MIT License. See the [LICENSE file](https://github.com/ppi/jquery-module/blob/master/LICENSE) for details.

Authors
-------

Vítor Brandão - <vitor@noiselabs.org> ~ [twitter.com/noiselabs](http://twitter.com/noiselabs) ~ [noiselabs.org](http://noiselabs.org)

See also the list of [contributors](https://github.com/ppi/jquery-module/contributors) who participated in this project.

Submitting bugs and feature requests
------------------------------------

Bugs and feature requests are tracked on [GitHub](https://github.com/ppi/jquery-module/issues).
