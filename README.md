# python-percy-client

[![Package Status](https://img.shields.io/pypi/v/percy.svg)](https://pypi.python.org/pypi/percy)
[![Build Status](https://travis-ci.org/percy/python-percy-client.svg?branch=master)](https://travis-ci.org/percy/python-percy-client)

Python client library for visual regression testing with [Percy](https://percy.io).

**Note**: This SDK has been deprecated in favor of our new Python SDK (which matches the API of all our other SDKS): https://github.com/percy/percy-python-selenium

## Usage

#### Docs here: [https://percy.io/docs/clients/python/selenium](https://percy.io/docs/clients/python/selenium)

## Contributing

### Setup for development

```bash
$ sudo easy_install pip
$ pip install virtualenv
$ virtualenv env
$ source env/bin/activate
$ make develop
```

Development:

```bash
source env/bin/activate
make test
make tdd
```
