# prototype-indexof-shim

[![Build Status](https://api.travis-ci.org/attila/prototype-indexof-shim.svg?branch=master)](https://travis-ci.org/attila/prototype-indexof-shim)

Browser shim for Array.prototype.indexOf as seen on [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexof)

This is most likely useful in a project built with [Browserify](http://browserify.org/) where <= IE8 compatibility is required.

## Installation

`npm install prototype-indexof-shim --save`

## Usage

`require('prototype-indexof-shim');`

This will not override the native method.
