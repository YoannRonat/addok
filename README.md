# Addok

Search engine for address. Only address.

Addok will index your address data and provide an HTTP API for full text search.

It is extensible with [plugins](http://addok.readthedocs.io/en/latest/plugins/),
for example for geocoding CSV files.

Used in production by France administration, with around 26 millions addresses.
In those servers, full France data is imported in about 15 min and it scales
to around 2000 searches per second.

Check the [documentation](http://addok.readthedocs.org/en/latest/) and a
[demo](http://adresse.data.gouv.fr/map/) with French data.

Powered by Python and Redis.

[![Build Status](https://travis-ci.org/addok/addok.svg?branch=master)](https://travis-ci.org/addok/addok)
[![Requirements Status](https://requires.io/github/addok/addok/requirements.svg?branch=master)](https://requires.io/github/addok/addok/requirements/?branch=master)
[![PyPi version](https://img.shields.io/pypi/v/addok.svg)](https://pypi.python.org/pypi/addok/)
[![Coverage Status](https://coveralls.io/repos/addok/addok/badge.svg?branch=master&service=github)](https://coveralls.io/github/addok/addok?branch=master)
