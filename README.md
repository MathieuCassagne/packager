level-packager
==============

<img alt="LevelDB Logo" height="100" src="http://leveldb.org/img/logo.svg">

> `levelup` package helper for distributing with an `abstract-leveldown` compatible back-end

![Node version](https://img.shields.io/badge/Node.js-%3E%3D6.0.0-orange.svg?style=flat-square)
[![Build Status](https://secure.travis-ci.org/Level/packager.png)](http://travis-ci.org/Level/packager)
[![dependencies](https://david-dm.org/Level/packager.svg)](https://david-dm.org/level/packager)
[![Greenkeeper badge](https://badges.greenkeeper.io/Level/packager.svg)](https://greenkeeper.io/)

[![NPM](https://nodei.co/npm/level-packager.png?stars&downloads)](https://nodei.co/npm/level-packager/)
[![NPM](https://nodei.co/npm-dl/level-packager.png)](https://nodei.co/npm/level-packager/)

**level-packager** exports single function which takes a single argument, an `abstract-leveldown` compatible storage back-end for [`levelup`](https://github.com/Level/levelup). The function returns a constructor function that will bundle `levelup` with the given `abstract-leveldown` replacement. The full API is supported, including optional functions, `destroy()`, and `repair()`. Encoding functionality is provided by [`encoding-down`](https://github.com/Level/encoding-down).

For example use-cases, see:

* [`level`](https://github.com/Level/level)
* [`level-mem`](https://github.com/Level/level-mem)
* [`level-hyper`](https://github.com/Level/level-hyper)
* [`level-lmdb`](https://github.com/Level/level-lmdb)

Also available is a *test.js* file that can be used to verify that the user-package works as expected.

<a name="contributing"></a>
Contributing
------------

**level-packager** is an **OPEN Open Source Project**. This means that:

> Individuals making significant and valuable contributions are given commit-access to the project to contribute as they see fit. This project is more like an open wiki than a standard guarded open source project.

See the [contribution guide](https://github.com/Level/community/blob/master/CONTRIBUTING.md) for more details.

<a name="license"></a>
License &amp; Copyright
-------------------

Copyright (c) 2012-2017 **level-packager** [contributors](https://github.com/level/community#contributors).

**level-packager** is licensed under the MIT license. All rights not explicitly granted in the MIT license are reserved. See the included `LICENSE.md` file for more details.
