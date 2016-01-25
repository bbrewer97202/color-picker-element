# &lt;color-picker&gt;

A custom HTML element that provides a color picker.

## Demo
[See demo](http://bbrewer97202.github.io/color-picker-element/demo/index.html)

## Overview
This is a generic custom element that is not built on third-party frameworks (Polymer, x-tag, etc). It will run in a browser that supports custom elements, shadow DOM and HTML imports.  For browsers that do not support these features, use the [webcomponents.js](https://github.com/WebComponents/webcomponentsjs) polyfills (the demo page uses a cdn hosted instance).

## Install

Install using [Bower](http://bower.io/):

```sh
$ bower install color-picker-element --save
```

## Usage

1. Import Web Components polyfill:

    ```html
    <script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.7.20/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/color-picker-element/dist/color-picker.html">
    ```

3. Embed on page, optionally providing width and height attributes

    ```html
    <color-picker width="200" height="200"></color-picker>
    ```

## License

[MIT License](http://opensource.org/licenses/MIT)
