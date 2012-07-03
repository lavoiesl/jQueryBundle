Symfony 2 jQuery Bundle
=======================

## Current Version

jQuery 1.7.2
jQuery UI 1.8.21

## Installation

### Add bundle in your `composer.json`

    {
        "require": {
            "lavoiesl/jquery-bundle": "*"
        }
    }

### Add bundle to your application kernel

    // app/AppKernel.php
    public function registerBundles()
    {
        $bundles = array(
            // ...
            new LavoieSl\jQueryBundle\LavoieSljQueryBundle(),
            // ...
        );
    }

Licenses
--------
Refer to the source code of the included files for license information

References
----------
[1]: http://jquery.com
[2]: http://jqueryui.com
[3]: http://symfony.com