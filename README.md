base64-js
=========

`base64-js` does basic base64 encoding/decoding in pure JS.

[![build status](https://secure.travis-ci.org/beatgammit/base64-js.png)](http://travis-ci.org/beatgammit/base64-js)

Many browsers already have base64 encoding/decoding functionality, but it is for text data, not all-purpose binary data.

Sometimes encoding/decoding binary data in the browser is useful, and that is what this module does.

## install

With [npm](https://npmjs.org) do:

`npm install @guld/base64-js` and `import base64js from '../base64-js/base64.js'`

For use in web browsers do:

`<script src="base64js.min.js"></script>`

## methods

`base64js` has three exposed functions, `byteLength`, `toByteArray` and `fromByteArray`, which both take a single argument.

* `byteLength` - Takes a base64 string and returns length of byte array
* `toByteArray` - Takes a base64 string and returns a byte array
* `fromByteArray` - Takes a byte array and returns a base64 string

## license

MIT
