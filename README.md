# README

[![Build Status](https://secure.travis-ci.org/egeloen/IvoryOrderedFormBundle.png)](http://travis-ci.org/egeloen/IvoryOrderedFormBundle)

The bundle allows to order your Symfony2 form fields by adding the position option. A position can either be first,
last or an associative array describing before and/or after field.

## Documentation

### Installation

Require the bundle in your composer.json file:

``` json
{
    "require": {
        "egeloen/ordered-form-bundle": "~1.0",
    }
}
```

Register the bundle:

``` php
// app/AppKernel.php

public function registerBundles()
{
    return array(
        new Ivory\OrderedFormBundle\IvoryOrderedFormBundle(),
        // ...
    );
}
```

Install the bundle:

``` bash
$ composer update
```

### Usage

As explain above, the bundle adds a new option called `position` on all forms! You can get the full documentation
[here](https://github.com/egeloen/ivory-ordered-form/blob/master/doc/usage.md#position).

### Known limitations

Some use cases can not be handled by the bundle. They are listed
[here](https://github.com/egeloen/ivory-ordered-form/blob/master/doc/known_limitations.md).

## Contribute

We love contributors! Ivory is an open source project. If you'd like to contribute, feel free to propose a PR!

## License

The Ivory Ordered Form Bundle is under the MIT license. For the full copyright and license information, please read the
[LICENSE](https://github.com/egeloen/IvoryOrderedFormBundle/blob/master/LICENSE) file that was distributed with this
source code.
