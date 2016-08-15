# Lenovit
Lenovit is a brand new LESS/JS framework for rapid website developement. Similar to bootstrap it comes with a bunch of components with which you can create awesome mobile-first websites with a lot of configuration options in no time. It is still in an early state of developement (pre-alpha) and currently just a one-man project. The **first alpha is not yet available**, so code and syntax may as well chang at anytime before final release.

## So why another CSS/HTML Framework?
- Many Lenovit modules are realised with flexbox, the future layout technology. Flexbox components render much faster than their float or inline-block equivalent and provide more layout options. 
- Most frameworks rely on SASS and some are even changing from LESS to SASS (like Bootstrap v4). If LESS is your pre-processor of choice, Lenovit is for you.  
- BEM-Syntax (with a few exceptions) for easy understanding and readable code.

## What's included:
- Gruntfile configured to compile (less), minify (CSS + JS + Images + SVG images + AppIcons) and compress files via gzip (CSS + JS + SVG images) 
- Sleek HTML 5 Boilerplate / Starter-Template with some minor modifications to system default behaviours for better organized project structures

## Browser-support
Lenovit will not support IE versions prior to 11 due to the lack of full support for features like flexbox and others. There is of course workarounds for the lack of features, but in most cases they can only be realised by polyfills, complex JS-logic or global/hacky CSS-selectors like *, which slow down rendering and create more (messy) code. Market share of older IE's has dropped heavily, so it's about time to focus on newer and faster technologies. If you wish to support IE10 or lower, consider using Bootstrap or another framework.

What browsers are/will be supported?
* Chrome 52
* Firefox 48
* Internet Explorer 11
* Edge
* Opera
* Safari (not yet tested)

## Documentation & Demos
The documentation is currently under progress. Please be patient.

## Useful reads:
Right setup of your head: https://github.com/joshbuchea/HEAD


## Dependencies:
- JQuery
- Modernizr (https://github.com/Modernizr/Modernizr)
- https://github.com/leongersen/wnumb
- https://github.com/leongersen/noUiSlider
- https://github.com/amsul/pickadate.js



## Author and Creator

**Dennis Hochhaus**

* <https://twitter.com/systemruhr>
* <https://facebook.com/systemruhr>
* <https://github.com/systemruhr>
* <http://www.systemruhr.de>

## Copyright and license
Code and documentation Copyright 2016 Dennis Hochhaus (SystemRuhr). Code released under [the MIT license](https://github.com/systemruhr/lenovit/blob/master/LICENSE).
