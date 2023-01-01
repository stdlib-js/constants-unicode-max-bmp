<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Max Code Point

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Maximum [Unicode][unicode] code point in the Basic Multilingual Plane (BMP).



<section class="usage">

## Usage

```javascript
import UNICODE_MAX_BMP from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-unicode-max-bmp@esm/index.mjs';
```

#### UNICODE_MAX_BMP

Maximum [Unicode][unicode] code point in the Basic Multilingual Plane (BMP).

```javascript
var bool = ( UNICODE_MAX_BMP === 65535 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import randu from 'https://cdn.jsdelivr.net/gh/stdlib-js/random-base-randu@esm/index.mjs';
import floor from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-floor@esm/index.mjs';
import fromCodePoint from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-from-code-point@esm/index.mjs';
import UNICODE_MAX_BMP from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-unicode-max-bmp@esm/index.mjs';

var x;
var i;

for ( i = 0; i < 100; i++ ) {
    x = floor( randu() * UNICODE_MAX_BMP );
    console.log( fromCodePoint( x ) );
}

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/constants/unicode/max`][@stdlib/constants/unicode/max]</span><span class="delimiter">: </span><span class="description">maximum Unicode code point.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-unicode-max-bmp.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-unicode-max-bmp

[test-image]: https://github.com/stdlib-js/constants-unicode-max-bmp/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/constants-unicode-max-bmp/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-unicode-max-bmp/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-unicode-max-bmp?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-unicode-max-bmp.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-unicode-max-bmp/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-unicode-max-bmp/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-unicode-max-bmp/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-unicode-max-bmp/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-unicode-max-bmp/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-unicode-max-bmp/main/LICENSE

[unicode]: https://en.wikipedia.org/wiki/Unicode

<!-- <related-links> -->

[@stdlib/constants/unicode/max]: https://github.com/stdlib-js/constants-unicode-max/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
