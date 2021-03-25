WizCoin
======

A Python module to represent the gallen, sickle, and knut coins for wizard currency.

Installation
------------

To install with pip, run:

    pip install wizcoin

Quickstart Guide
----------------

Here's some example code demonstrating how this module is used:

    >>> import wizcoin
    >>> coin = wizcoin.Wizcoin(2, 5, 10)
    >>> str(coin)
    '2g, 5s, 10k'
    >>> coin.value()
    1411

Contribute
----------

If you'd like to contribute to WizCoin, check out https://github.com/asweigart/wizcoin
