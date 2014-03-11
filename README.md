# Stacey 3.0.0

## Overview
Stacey takes content from `.yml` files, image files and implied directory structure and generates a website.
It is a no-database, dynamic website generator.

If you look in the `/content` and `/templates` folders, you should get the general idea of how it all works.

## Installation

Copy to server, `chmod 777 app/_cache`.

If you want clean urls, `mv htaccess .htaccess`

## Templates

This version of stacey includes a template featuring bootstrap.

Stacey uses the [Twig templating language](http://twig.sensiolabs.org/).

There are an additional two sets of templates which can be found at:
<http://github.com/kolber/stacey-template2> &
<http://github.com/kolber/stacey-template3>

## Read More

See <http://staceyapp.com> for more detailed usage information.

## Copyright/License

Copyright (c) 2009 Anthony Kolber. See `LICENSE` for details.
Except:  
* [PHP Markdown Extra](http://michelf.com/projects/php-markdown/extra/) which is (c) Michel Fortin (see `app/parsers/markdown-parser.inc.php` for details),
* [Bootstrap](http://getbootstrap.com) which is (c) Twitter, Inc. (see `public/js/bootstrap.js` for details),
* [jQuery](http://jquery.com) which is (c) jQuery Foundation, Inc. and others (see `public/js/jquery.js` for details),
* [Minify_HTML](http://code.google.com/p/minify/) which is (c) Stephen Clay (see `app/parsers/html-minifier/HTML.php` for details),
* [jsmin.php](https://github.com/rgrove/jsmin-php/) which is (c) Ryan Grove (see `app/parsers/json-minifier.inc.php` for details) and
* [less](http://lesscss.org) which is (c) Alexis Sellier (see `public/js/less.js` for details).
