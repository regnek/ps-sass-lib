# PS Sass Library

*Helpful base styles to expedite workflow and create a better product*

## Other PS Resources

- [CSS/Sass Style Guide](https://github.com/regnek/ps-css)
- [JavaScript Style Guide](https://github.com/regnek/ps-js)
- [Snippet Library](https://github.com/regnek/ps-snippet-lib)

## Table of Contents

1. [Mixins](#mixins)
    - [Flexbox](#flexbox)
    - [Grid](#grid-mixin)
    - [Box shadow](#ordering-of-property-declarations)
    - [Media queries](#media-queries)
    - [Gradients](#gradients)
    - [Color modifiers](#color-modifiers)
1. [Helpers](#helpers)
    - [Margin](#margin)
    - [Padding](#padding)
    - [Hiding elements](#hiding-elements)
    - [Flex](#flex)
    - [Images](#images)
    - [Positioning](#positioning)
    - [Overflow](#overflow)
    - [Typography](#typography)
1. [Layout](#layout)
    - [Grid](#grid)
    - [Rows](#rows)
    - [Columns](#columns)


## Mixins

### Flexbox

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
  @include flex(center, center);
}
```

### Grid

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

### Flex 

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