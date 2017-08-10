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
* `python-setuptools`, the Python Packaging ecosystem
* `python-pip`, the Python Packaging ecosystem
* `python-wheel`, Used for unbundling of pip and setuptools

#### Dependencies
* `net-tools`, build dependency of the `python3` package
* `tk`, build dependency of the `python3` and `tix` packages
* `tix`, build dependency of the `python3` package


### `python3-bootstrap`

This module is necessary to bootstrap the `python3` module.

#### Main packages
* `python3`, the main Python language interpreter
* `python-setuptools`, the Python Packaging ecosystem
* `python-pip`, the Python Packaging ecosystem
* `python-wheel`, Used for unbundling of pip and setuptools

#### Dependencies
* `net-tools`, build dependency of the `python3` package
* `tk`, build dependency of the `python3` and `tix` packages
* `tix`, build dependency of the `python3` package


### `python3-ecosystem`

[To be added in the future.]
This module will contain the same packages as the rh-python36 Software Collection plus their new dependencies.


### `python3-ecosystem-bootstrap`

[To be added in the future.]
This module will enable the bootstrapping sequence of the `python3-sphinx` package for the `python3-ecosystem` module.
