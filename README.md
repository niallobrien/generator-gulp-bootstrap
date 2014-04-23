# Web app generator [![Build Status](https://secure.travis-ci.org/yeoman/generator-gulp-webapp.svg?branch=master)](http://travis-ci.org/yeoman/generator-gulp-webapp)

[Yeoman](http://yeoman.io) generator that scaffolds out a front-end web app using [Gulp](http://gulpjs.com/) for the build process.

## Features

* Built-in preview server with BrowserSync *(new)*
* CSS Autoprefixing *(new)*
* Automagically compile Sass (via libsass) *(new)*
* Automagically lint your scripts
* Awesome Image Optimization (via OptiPNG, pngquant, jpegtran and gifsicle)
* Automagically wire-up dependencies installed with [Bower](http://bower.io) (when `gulp watch` or `gulp wiredep`)
* TODO: Mocha Unit Testing with PhantomJS
* TODO: Optional - Leaner Modernizr builds *(new)*


## Getting Started

- Install: `npm install -g generator-gulp-bootstrap`
- Run: `yo gulp-bootstrap`
- Run `gulp` for building and `gulp watch` for preview


#### Third-Party Dependencies

*(HTML/CSS/JS/Images/etc)*

To install dependencies, run `bower install depName --save` to get the files, then add a `script` or `style` tag to your `index.html` or an other appropriate place.

## Options

* `--skip-install`

  Skips the automatic execution of `bower` and `npm` after scaffolding has finished.

* `--test-framework=<framework>`

  Defaults to `mocha`. Can be switched for another supported testing framework like `jasmine`.


## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
