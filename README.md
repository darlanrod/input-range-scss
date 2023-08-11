# Styling Cross-Browser Compatible Range Inputs with Sass / SCSS

Sass component for customizing the input range using the native properties of each browser. Based on article [Styling Cross-Browser Compatible Range Inputs with CSS](https://css-tricks.com/styling-cross-browser-compatible-range-inputs-css/) from CSS Tricks blog.

## NPM Package
```
npm i input-range-scss
```
## Features

-   Variables for easy customization
-   Uses the native properties of each browser
-   Preserves accessibility
-   Cross-browser compatible

## Example

![Input range native and custom on browsers](https://github.com/darlanrod/input-range-scss/raw/master/example/input-range-browsers.jpg)

## Usage

To use this library in your stylesheets, import it as a Sass module:

```
@use 'input-range-scss';
```
To override the default styling, use the `with` keyword along with any variables you would like to override, for example:

```
@use 'input-range-scss' with (
  $track-color: red,
  $thumb-color: blue,
  $thumb-height: 2em,
  $thumb-width: 2em,
);
```

For a complete list of variables see https://github.com/darlanrod/input-range-scss/blob/master/_inputrange.scss#L9.

NB. including the module will apply styles all elements matching the CSS selector `[type='range']`.

## Changelog

To see the change history of this project, check out the `changelog.md` file.

## See Also

[Input range browser support](http://caniuse.com/#feat=input-range)
