# Simpler version of [Web app generator](https://github.com/yeoman/generator-gulp-webapp)

> [Yeoman](http://yeoman.io) generator that scaffolds out a front-end web app using [gulp](http://gulpjs.com/) for the build process

## What was removed

* Initial prompt (Modernizr, Bootstrap)
* jQuery
* Analytics from index.html template

## Features

Please see our [gulpfile.js](app/templates/gulpfile.js) for up to date information on what we support.

* CSS Autoprefixing
* Built-in preview server with livereload and browser synchronization (new)
* Automagically compile Sass
* Automagically lint your scripts
* Awesome image optimization
* Automagically wire-up dependencies installed with [Bower](http://bower.io) *(when `gulp watch` or `gulp wiredep`)*

*For more information on what this generator can do for you, take a look at the [gulp plugins](app/templates/_package.json) used in our `package.json`.*


## Getting Started

- Clone: `git clone https://github.com/Hodes/generator-gulp-webapp generator-simpler-gulp-webapp` (folder name matters)
- Get into it: `cd generator-simpler-gulp-webapp`
- Create link: `npm link`
- In your new project folder run: `yo simpler-gulp-webapp`
- Run `gulp` for building to the `dist` directory and `gulp serve` for preview


#### Third-Party Dependencies

*(HTML/CSS/JS/Images/etc)*

To install dependencies, run `bower install --save package-name` to get the files, then add a `script` or `style` tag to your `index.html` or another appropriate place.


## Docs

We have [recipes](docs/recipes/README.md) for integrating other popular technologies like CoffeeScript.


## Options

- `--skip-install`
  Skips the automatic execution of `bower` and `npm` after scaffolding has finished.

- `--test-framework=<framework>`
  Defaults to `mocha`. Can be switched for another supported testing framework like `jasmine`.


## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
