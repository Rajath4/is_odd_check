# is_odd_check

# is-odd [![NPM version](https://img.shields.io/npm/v/is-odd.svg?style=flat)](https://www.npmjs.com/package/is-odd) [![NPM monthly downloads](https://img.shields.io/npm/dm/is-odd.svg?style=flat)](https://npmjs.org/package/is-odd) [![NPM total downloads](https://img.shields.io/npm/dt/is-odd.svg?style=flat)](https://npmjs.org/package/is-odd) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/is-odd.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/is-odd)

> Returns true if the given number is odd, and is an integer that does not exceed the JavaScript MAXIMUM_SAFE_INTEGER.

Please consider following this project's author, [Jon Schlinkert](https://github.com/jonschlinkert), and consider starring the project to show your :heart: and support.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save is-odd
```

## Usage

Works with strings or numbers.

```js
const isOdd = require("is_odd_check");

console.log(isOdd("1")); //=> true
console.log(isOdd("3")); //=> true

console.log(isOdd(0)); //=> false
console.log(isOdd(2)); //=> false
```

## About

<details>
<summary><strong>Contributing</strong></summary>

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

</details>

<details>
<summary><strong>Running Tests</strong></summary>

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

</details>
