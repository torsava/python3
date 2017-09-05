# Python 3 module(s)

Tracking the top-level packages of the Python 3 module, or modules.

The new modules target modular Fedora releases, starting with version 27.

This main purpose of this repository is being the content tracker. The format is based on the [Host and Platform](https://github.com/fedora-modularity/hp) definition.

## Content definition

This section includes a list of modules along with toplevel binary input packages for package-level dependency resolution.


### `python3`

The Python programming language, version 3.

#### Main packages
* `python3`, the main Python language interpreter
* `python3-libs`, the Python standard library
* `python3-pip`, Python packaging ecosystem
* `python3-setuptools`, Python packaging ecosystem

#### Devel packages
* `python3-debug`, for debugging purposes
* `python3-devel`, for development
* `python3-tools`, tools for development
* `python3-wheel`, a built-package format for Python


### `python3-bootstrap`

This module is necessary to bootstrap the `python3` module.

#### Packages
Packages will be the same as in the `python3` module but will not be officially supported beyond bootstrapping the `python3` module.


### `python3-ecosystem`

**Current state, Not final**

* `python-systemd-doc`
* `python3-cryptography`
* `python3-custodia`
* `python3-custodia-extra`
* `python3-dns`
* `python3-jwcrypto`
* `python3-pluggy`
* `python3-python-etcd`
* `python3-systemd`
* `python3-tox`


### `python3-ecosystem-bootstrap`

[To be added in the future.]
This module will enable the bootstrapping of the `python3-ecosystem` module.

