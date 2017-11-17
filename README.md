w-signal-ws
==========

<!---
This file is generated by ape-tmpl. Do not update manually.
--->

<!-- Badge Start -->
<a name="badges"></a>

[![Build Status][bd_travis_shield_url]][bd_travis_url]
[![npm Version][bd_npm_shield_url]][bd_npm_url]
[![JS Standard][bd_standard_shield_url]][bd_standard_url]

[bd_repo_url]: https://github.com/realglobe-Inc/w-signal-ws
[bd_travis_url]: http://travis-ci.org/realglobe-Inc/w-signal-ws
[bd_travis_shield_url]: http://img.shields.io/travis/realglobe-Inc/w-signal-ws.svg?style=flat
[bd_travis_com_url]: http://travis-ci.com/realglobe-Inc/w-signal-ws
[bd_travis_com_shield_url]: https://api.travis-ci.com/realglobe-Inc/w-signal-ws.svg?token=
[bd_license_url]: https://github.com/realglobe-Inc/w-signal-ws/blob/master/LICENSE
[bd_codeclimate_url]: http://codeclimate.com/github/realglobe-Inc/w-signal-ws
[bd_codeclimate_shield_url]: http://img.shields.io/codeclimate/github/realglobe-Inc/w-signal-ws.svg?style=flat
[bd_codeclimate_coverage_shield_url]: http://img.shields.io/codeclimate/coverage/github/realglobe-Inc/w-signal-ws.svg?style=flat
[bd_gemnasium_url]: https://gemnasium.com/realglobe-Inc/w-signal-ws
[bd_gemnasium_shield_url]: https://gemnasium.com/realglobe-Inc/w-signal-ws.svg
[bd_npm_url]: http://www.npmjs.org/package/w-signal-ws
[bd_npm_shield_url]: http://img.shields.io/npm/v/w-signal-ws.svg?style=flat
[bd_standard_url]: http://standardjs.com/
[bd_standard_shield_url]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg

<!-- Badge End -->


<!-- Description Start -->
<a name="description"></a>

Web socket implementation of w-signal

<!-- Description End -->


<!-- Overview Start -->
<a name="overview"></a>



<!-- Overview End -->


<!-- Sections Start -->
<a name="sections"></a>

<!-- Section from "doc/guides/01.Installation.md.hbs" Start -->

<a name="section-doc-guides-01-installation-md"></a>

Installation
-----

```bash
$ npm install w-signal-ws --save
```


<!-- Section from "doc/guides/01.Installation.md.hbs" End -->

<!-- Section from "doc/guides/02.Usage.md.hbs" Start -->

<a name="section-doc-guides-02-usage-md"></a>

Usage
---------

```javascript
'use strict'

const wSignalWs = require('w-signal-ws')

async function tryExample () {
  const signal = await wSignalWs()
}

tryExample().catch((err) => console.error(err))

```


<!-- Section from "doc/guides/02.Usage.md.hbs" End -->

<!-- Section from "doc/guides/10.API Guide.md.hbs" Start -->

<a name="section-doc-guides-10-a-p-i-guide-md"></a>

API Guide
-----

+ [w-signal-ws@1.0.0](./doc/api/api.md)
  + [create(args)](./doc/api/api.md#w-signal-ws-function-create)
  + [WSignalWs](./doc/api/api.md#w-signal-ws-class)


<!-- Section from "doc/guides/10.API Guide.md.hbs" End -->


<!-- Sections Start -->


<!-- LICENSE Start -->
<a name="license"></a>

License
-------
This software is released under the [MIT License](https://github.com/realglobe-Inc/w-signal-ws/blob/master/LICENSE).

<!-- LICENSE End -->


<!-- Links Start -->
<a name="links"></a>

Links
------

+ [w][w_url]
+ [Realglobe, Inc.][realglobe,_inc__url]

[w_url]: https://github.com/realglobe-Inc/w
[realglobe,_inc__url]: http://realglobe.jp

<!-- Links End -->
