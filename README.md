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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Process

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Process utilities.

<section class="installation">

## Installation

```bash
npm install @omegion1npm/ipsum-culpa-accusamus
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var ns = require( '@omegion1npm/ipsum-culpa-accusamus' );
```

#### ns

Namespace containing process utilities.

```javascript
var proc = ns;
// returns {...}
```

The namespace contains process utilities:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`ARGV`][@omegion1npm/ipsum-culpa-accusamus/argv]</span><span class="delimiter">: </span><span class="description">array containing command-line arguments passed when launching the calling process.</span>
-   <span class="signature">[`chdir( path )`][@omegion1npm/ipsum-culpa-accusamus/chdir]</span><span class="delimiter">: </span><span class="description">change the current working directory.</span>
-   <span class="signature">[`cwd()`][@omegion1npm/ipsum-culpa-accusamus/cwd]</span><span class="delimiter">: </span><span class="description">return the current working directory.</span>
-   <span class="signature">[`ENV`][@omegion1npm/ipsum-culpa-accusamus/env]</span><span class="delimiter">: </span><span class="description">object containing the user environment.</span>
-   <span class="signature">[`EXEC_PATH`][@omegion1npm/ipsum-culpa-accusamus/exec-path]</span><span class="delimiter">: </span><span class="description">absolute pathname of the executable which started the current Node.js process.</span>
-   <span class="signature">[`getegid()`][@omegion1npm/ipsum-culpa-accusamus/getegid]</span><span class="delimiter">: </span><span class="description">return the effective numeric group identity of the calling process.</span>
-   <span class="signature">[`geteuid()`][@omegion1npm/ipsum-culpa-accusamus/geteuid]</span><span class="delimiter">: </span><span class="description">return the effective numeric user identity of the calling process.</span>
-   <span class="signature">[`getgid()`][@omegion1npm/ipsum-culpa-accusamus/getgid]</span><span class="delimiter">: </span><span class="description">return the numeric group identity of the calling process.</span>
-   <span class="signature">[`getuid()`][@omegion1npm/ipsum-culpa-accusamus/getuid]</span><span class="delimiter">: </span><span class="description">return the numeric user identity of the calling process.</span>
-   <span class="signature">[`NODE_VERSION`][@omegion1npm/ipsum-culpa-accusamus/node-version]</span><span class="delimiter">: </span><span class="description">node version.</span>
-   <span class="signature">[`stdin( [encoding,] clbk )`][@omegion1npm/ipsum-culpa-accusamus/read-stdin]</span><span class="delimiter">: </span><span class="description">read data from `stdin`.</span>
-   <span class="signature">[`umask( [mask,] [options] )`][@omegion1npm/ipsum-culpa-accusamus/umask]</span><span class="delimiter">: </span><span class="description">get/set the process mask.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils/keys' );
var ns = require( '@omegion1npm/ipsum-culpa-accusamus' );

console.log( objectKeys( ns ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@omegion1npm/ipsum-culpa-accusamus.svg
[npm-url]: https://npmjs.org/package/@omegion1npm/ipsum-culpa-accusamus

[test-image]: https://github.com/omegion1npm/ipsum-culpa-accusamus/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/omegion1npm/ipsum-culpa-accusamus/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/omegion1npm/ipsum-culpa-accusamus/main.svg
[coverage-url]: https://codecov.io/github/omegion1npm/ipsum-culpa-accusamus?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/omegion1npm/ipsum-culpa-accusamus.svg
[dependencies-url]: https://david-dm.org/omegion1npm/ipsum-culpa-accusamus/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/deno
[deno-readme]: https://github.com/omegion1npm/ipsum-culpa-accusamus/blob/deno/README.md
[umd-url]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/umd
[umd-readme]: https://github.com/omegion1npm/ipsum-culpa-accusamus/blob/umd/README.md
[esm-url]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/esm
[esm-readme]: https://github.com/omegion1npm/ipsum-culpa-accusamus/blob/esm/README.md
[branches-url]: https://github.com/omegion1npm/ipsum-culpa-accusamus/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/omegion1npm/ipsum-culpa-accusamus/main/LICENSE

<!-- <toc-links> -->

[@omegion1npm/ipsum-culpa-accusamus/argv]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/argv

[@omegion1npm/ipsum-culpa-accusamus/chdir]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/chdir

[@omegion1npm/ipsum-culpa-accusamus/cwd]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/cwd

[@omegion1npm/ipsum-culpa-accusamus/env]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/env

[@omegion1npm/ipsum-culpa-accusamus/exec-path]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/exec-path

[@omegion1npm/ipsum-culpa-accusamus/getegid]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/getegid

[@omegion1npm/ipsum-culpa-accusamus/geteuid]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/geteuid

[@omegion1npm/ipsum-culpa-accusamus/getgid]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/getgid

[@omegion1npm/ipsum-culpa-accusamus/getuid]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/getuid

[@omegion1npm/ipsum-culpa-accusamus/node-version]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/node-version

[@omegion1npm/ipsum-culpa-accusamus/read-stdin]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/read-stdin

[@omegion1npm/ipsum-culpa-accusamus/umask]: https://github.com/omegion1npm/ipsum-culpa-accusamus/tree/main/umask

<!-- </toc-links> -->

</section>

<!-- /.links -->
