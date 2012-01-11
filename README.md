Symfony 2 jQuery Bundle
=======================

## Current Version

jQuery 1.7.1

## Installation

### Add bundle to your vendor folder

    git submodule add git://github.com/ManyMules/ManyMulesJQueryBundle.git vendor/bundles/ManyMules/Bundle/JQueryBundle

### Add bundle to your application kernel

    // app/AppKernel.php
    public function registerBundles()
    {
        $bundles = array(
            // ...
            new ManyMules\Bundle\JQueryBundle\ManyMulesJQueryBundle(),
            // ...
        );
    }

### Add ManyMules bundles folder to autoload

    // app/autoload.php
    $loader->registerNamespaces(array(
        ...
        'ManyMules\Bundle'               => __DIR__.'/../vendor/bundles',
        ...
    ));

Licenses
--------
Refer to the source code of the included files for license information

References
----------
[1]: http://jquery.com
[2]: http://symfony.com