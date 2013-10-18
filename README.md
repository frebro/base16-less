base16-less
===========

A LESS implementation of the [Base16 color schemes](https://github.com/chriskempson/base16), originally by Chris Kempson.

Installation
------------

[Download the ZIP](https://github.com/frebro/base16-less/archive/master.zip) or install with [bower](http://bower.io/):

``` bash
bower install base16-less
```

How to use
----------

Inside the /base16 directory are a number of Base16 color theme files. Include one of them in your project to get access to color variables.

These are the available variable names:

``` less
// Grayscale
@base00 @base01 @base02 @base03 @base04 @base05 @base06 @base07

// Colors
@base08 @base09 @base0A @base0B @base0C @base0D @base0E @base0F
```

Themes included
---------------

By [Bram de Haan](http://atelierbram.github.io/syntax-highlighting/atelier-schemes/)
* Atelier Dune
* Atelier Forest
* Atelier Heath
* Atelier Lakeside
* Atelier Seaside

By [Chris Kempson](http://chriskempson.com)
* Bright
* Chalk
* Default
* Eighties
* Greenscreen
* Mocha
* Ocean
* Pop
* Tomorrow

By [Wimer Hazenberg](http://www.monokai.nl)
* Monokai

By [Ryan Bates](http://railscasts.com)
* Railscasts

By [Ethan Schoonover](http://ethanschoonover.com/solarized)
* Solarized

Bootstrap integration
---------------------

Do you build your own [Bootstrap](https://github.com/twbs/bootstrap)? Include either one of base16-light or base16-dark from the /bootstrap/ directory together with one of the theme files to apply a Base16 color theme. Here's how

``` css
// Import Bootstrap
@import "bootstrap";

// Apply a Base16 theme
@import "base16/default"
@import "bootstrap/base16-dark"
```
