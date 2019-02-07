# PyBagIt 2.0.0-alpha-1
[![Build Status](https://travis-ci.com/deepio/pybagit.svg?branch=master)](https://travis-ci.com/deepio/pybagit)
[![PyPI version fury.io](https://badge.fury.io/py/pybagit.svg)](https://pypi.python.org/pypi/pybagit/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)


This module helps with creating and managing BagIt-compliant packages. It has
been created to conform to __BagIt v0.97__.

Documentation is available at http://ahankinson.github.io/pybagit.
Code hosting is available on GitHub at http://github.com/ahankinson/pybagit/.

## Requirements
- Tested with Python `3.6`, `3.7`
- No external modules required.
- Module has not been tested on Windows.

## Running Tests
There are a number of unit tests written to verify that this module functions
as expected. To run this, simply type `python setup.py test` in the package directory.

__NOTE:__ You will need a network connection to verify
the 'fetch' tests. If you don't have a network connection you can skip these
tests by commenting them out in `bagtest.py`

## Setup and Install
To install this module, simply run:
- `python setup.py install`

(__Do not install any python module with sudo, unless you are using a very obscure OS that requires it.__)
