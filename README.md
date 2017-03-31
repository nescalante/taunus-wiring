Taunus-wiring
=============

[![Greenkeeper badge](https://badges.greenkeeper.io/nescalante/taunus-wiring.svg)](https://greenkeeper.io/)

This module is a plugin for [browserify](http://browserify.org/) to generate the [Taunus](https://github.com/taunus/taunus) wiring object.

## usage

```js
var taunus = require('taunus');
var main = document.getElementsByTagName('main')[0];
var wiring = require('taunus-wiring')();

taunus.mount(main, wiring);
````

## on the command line

browserify -t taunus-wiring main.js -o bundle.js
