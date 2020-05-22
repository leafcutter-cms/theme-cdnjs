# Leafcutter CDN libraries

## Installation

This package is meant to be installed via Composer, it can be installed with `composer require leafcutter/theme-cdnjs`

## What's in it

This package overrides the built-in libraries to use copies from cdnjs.com instead of internal copies.

### Library packages

#### `library/fontawesome`

Provides just the CSS and font files of Font Awesome Free. None of Font Awesome's Javascript is included in this package.

#### `library/jquery`

Provides just a minified production-ready copy of jQuery.

#### `library/jquery-ui`

Provides jQuery UI's Javascript. jQuery UI's CSS is not overridden, as the core themes have some very worthwhile customizations.

#### `library/vue`

Provides just a minified production-ready copy of Vue.js
