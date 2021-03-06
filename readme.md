# Ghost theme development

<!-- MarkdownTOC -->

- Installation
- Gulp tasks
- Thanks

<!-- /MarkdownTOC -->

## Installation

1. Install [nodejs](http://nodejs.org).
2. Install [gulp](http://gulpjs.com): `npm install -g gulp`
4. Navigate into your directory.
5. Execute `npm install`
6. Execute `git clone git@github.com:chj1axr0/Ghost-Blank.git src`
7. Execute `gulp livereload` and open `localhost:2368` in your browser.

## Gulp tasks

Comes with three gulp tasks:

* `gulp default` builds the complete theme and dumps to `content/themes/dev/`
* `gulp livereload` starts a file watcher, a livereload server, and a ghost instance. If you change any files inside the `src` folder, they will get updated if you're connected to `localhost:2368`. Files inside that get moved to `content/themes/`_`theme-name`_`/`, where _theme-name_ is the name of your ghost theme taken from `src/package.json`.
* `gulp dist` minifies, concats and compresses the theme in `build/`_`theme-name`_`.zip`.

## Thanks
This is based on:
https://github.com/TF2Stadium/Ghost-Environment/tree/master

which in turn is based on:
http://blog.dunkelstern.de/2014/11/02/developing-ghost-templates/

Which has a repository at:
https://github.com/dunkelstern/ghost-theme-development/tree/master
