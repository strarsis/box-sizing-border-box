# box-sizing-border-box
Best practice for setting box-sizing: border-box.

From https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/ .


## Installation

Using `npm`:
`npm install --save-dev box-sizing-border-box`

Using `yarn`:
`yarn add --dev box-sizing-border-box`


## What's inside?
See https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/ .
```css
html {
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}
````


## Usage

### webpack (SCSS) + node_modules loader
```scss
@import "~box-sizing-border-box";
````

### eyeglass (SCSS):
```scss
@import 'box-sizing-border-box';
````
