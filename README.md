# PS Sass Library

*Helpful base styles to expedite workflow and get everyone using the same codebase*

## Other PS Resources

- [CSS/Sass Style Guide](https://github.com/regnek/ps-css)
- [JavaScript Style Guide](https://github.com/regnek/ps-js)
- [Snippet Library](https://github.com/regnek/ps-snippet-lib)

## Table of Contents

1. [How to Use](#how-to-use)
1. [Layout](#layout)
    - [Grid](#grid)
    - [Rows](#rows)
    - [Columns](#columns)
1. [Mixins](#mixins)
    - [Flex](#flex)
    - [Grid](#grid-mixin)
    - [Box shadow](#ordering-of-property-declarations)
    - [Media queries](#media-queries)
    - [Gradients](#gradients)
    - [Color modifiers](#color-modifiers)
1. [Helpers](#helpers)
    - [Margin](#margin)
    - [Padding](#padding)
    - [Hiding elements](#hiding-elements)
    - [Flex](#flex-helper)
    - [Images](#images)
    - [Positioning](#positioning)
    - [Overflow](#overflow)
    - [Typography](#typography)


## How to Use

To use our Sass library, simply download or clone this repository, and copy the *sass* folder found in this repository into your current project directory.

In your cli, enter the following command to make Sass continuously watch for changes, and write them to a file in a *css* folder.

```shell
~/project-folder $ sass --watch scss:css
```

You won't always need all of the helpers and mixins. Sometimes you might not use any of them. If that's the case, in your `main.scss` file, comment out whichever `@import` directives you don't need, and they won't be compiled to your css output.

## Layout

### Grid

In CSS, we specify our column size by the number of columns in the row, not by how many columns it takes up. The math is easier this way.

![grid system](https://github.com/regnek/ps-sass-lib/blob/master/doc-assets/sass-lib-grid-layout.jpg)

### Rows

The `row` class is the container for columns, and is displayed `flex` by default. This evenly distributes the columns within the rows.

> Note: This system is 

When the `row` breaks on mobile/tablet, it switches from `flex-direction: row` to `flex-direction: column` to place columns on top of each other.

**scss**

```scss
.row {
  display: flex;
  flex-direction: column;

  @media ($break-point) {
    flex-direction: row;
  }
}
```

**html**

```html
<div class="row">
  <div class="col-3"></div>
  <div class="col-3"></div>
  <div class="col-3"></div>
</div>
```


## Mixins

### Flex

```scss
@mixin flex($align, $justify, $direction: row) {
  display: flex;
  align-items: $align;
  justify-content: $justify;
  flex-direction: $direction;
}
```

The `flex` mixin allows you to add flex capabilities to any class, prescribing the subsequent properties `align-items`, `justify-content`, and `flex-direction` if desired.

**Example**

```scss
.section {
  padding: 5rem 0;
  @include flex(center, space-between);
}
```

### Grid Mixin

lorem ipsum

### Box shadow

lorem ipsum

### Media queries

lorem ipsum

### Gradients

lorem ipsum

### Color modifiers

lorem ipsum

**[Back to top](#table-of-contents)**

## Helpers

### Margin

lorem ipsum

### Padding

lorem ipsum

### Hiding elements

lorem ipsum

### Flex Helper

lorem ipsum

### Images

lorem ipsum

### Positioning

lorem ipsum

### Overflow

lorem ipsum

### Typography

lorem ipsum

**[Back to top](#table-of-contents)**

## Layout

### Grid

lorem ipsum

### Rows

lorem ipsum

### Columns

lorem ipsum

**[Back to top](#table-of-contents)**