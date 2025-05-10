# Styling Cross-Browser Compatible Range Inputs with Sass / SCSS

`input-range-scss` is a Sass component designed to simplify the customization of `<input type="range">` elements across all major browsers. It leverages native browser properties while maintaining accessibility and cross-browser compatibility. This library was created for developers and designers looking to create polished, consistent range sliders without sacrificing usability.

## Why Use `input-range-scss`?

- **Customizable**: Easily override default styles with Sass variables to match your design system.
- **Cross-Browser Compatibility**: Ensures consistent styling across Chrome, Firefox, Safari, Edge, and Internet Explorer.
- **Accessibility**: Preserves native accessibility features, ensuring your sliders are usable for all users.
- **Lightweight**: Focused on styling only, with no JavaScript dependencies.
- **Modern Sass Features**: Uses the latest Sass module system for clean and maintainable code.

## Installation

Install the package via NPM:

```
npm i input-range-scss
```

## Features

- Predefined variables for effortless customization
- Support for modern and legacy browsers
- Built-in mixins for shadows and other effects
- Modular Sass structure for easy integration

## Example

Below is an example of how the library can transform native range inputs into styled sliders:

![Input range native and custom on browsers](https://github.com/darlanrod/input-range-scss/raw/master/example/input-range-browsers.jpg)

## Usage

To use this library in your project, import it as a Sass module:

```scss
@use 'input-range-scss';
```

### Customizing Styles

Override the default styles by passing your own values to the Sass variables using the `with` keyword:

```scss
@use 'input-range-scss' with (
  $track-color: #ff5722,
  $thumb-color: #4caf50,
  $thumb-height: 20px,
  $thumb-width: 20px,
  $track-height: 10px,
);
```

### Available Variables

Here are some of the key variables you can customize:

- `$track-color`: The color of the slider track.
- `$thumb-color`: The color of the slider thumb.
- `$thumb-height`: The height of the slider thumb.
- `$thumb-width`: The width of the slider thumb.
- `$track-height`: The height of the slider track.
- `$contrast`: Adjusts the contrast for hover and active states.

For a complete list of variables, see the [source file](https://github.com/darlanrod/input-range-scss/blob/master/_inputrange.scss#L9).

## Changelog

To see the change history of this project, check out the [`changelog.md`](https://github.com/darlanrod/input-range-scss/blob/master/changelog.md) file.

## See Also

- [Input range browser support](http://caniuse.com/#feat=input-range)
- [CSS Tricks: Styling Cross-Browser Compatible Range Inputs](https://css-tricks.com/styling-cross-browser-compatible-range-inputs-css/)