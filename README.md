openLilyLib Project Web
=======================

This repository contains the complete web presence of www.openlilylib.org.
It is located at openLilyLib's GitHub home (https://github.com/openlilylib)

The web site is generated using the lightweight stacey Content Management System (http://www.staceyapp.com), which means that any content is to be added/updated through the text files below /content.
For some starting hints from the original stacey.com README see below at the end of this document.

The website itself isn't connected to the Git repository, so any changes should be first committed (preferably to `master`) and then uploaded/synchronized via ftp (you may ask for the login data).

The changes should then immediately be visible on http://www.openlilylib.org.

# Stacey 2.3.0

## Overview
Stacey takes content from `.txt` files which can use Markdown formatting, HTML tags and a set of custom fields.  
It is a no-database, dynamic website generator.

If you look in the `/content` and `/templates` folders, you should get the general idea of how it all works.

## Read More

See <http://staceyapp.com> for more detailed usage information.

## Copyright/License

Copyright (c) 2009 Anthony Kolber. See `LICENSE` for details.
Except PHP Markdown Extra which is (c) Michel Fortin (see `/app/parsers/markdown-parser.inc.php` for details) and
JSON.minify which is (c) Kyle Simpson (see 'app/parsers/json-minifier.inc.php' for details).