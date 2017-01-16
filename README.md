# \<slider-app\>

## Install the example

### 1. clone or fork this repo

### 2. run bower install
```
$ bower install
```

### 3. serve the application
```
$ polymer serve
```

This example is attached to issue 5 of polymer-simple-slide. Please refer to [the issue on Github](https://github.com/ruyadorno/polymer-simple-slider/issues/5) for more information.

What you see should be the example. With two sliders. One that is just like the standard example. The second is a slider that has images retrieved with iron-ajax and has different html markup. It isn't the html markup that is causing the bug. I found that it might be the async loading of the app script and webcomponents. Please advice!

------------

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
