# Child-Selector
# CSS Child Selectors Task

This project demonstrates the usage of **CSS child selectors** to target specific child elements inside various sections. The tasks include manipulating the layout, hiding certain elements, and styling specific child elements based on their positions using `:nth-child()` and `:nth-of-type()` selectors.

## Table of Contents

- [Task 1: Zig-Zag Boxes](#task-1-zig-zag-boxes)
- [Task 2: Hide Even Elements](#task-2-hide-even-elements)
- [Task 3: Advanced Selection](#task-4-advanced-selection)
- [Task 4: Image Display](#task-5-image-display)

## Task 1: Zig-Zag Boxes

In **Task 1**, we have 10 boxes within a `section`. The task is to style these boxes with alternating colors based on their position (odd/even) using CSS selectors.

### Key CSS Used:
- `section:first-of-type div`: Selects all `div` elements inside the first `section`.
- `section:nth-of-type(1) div:nth-child(even)`: Selects even-numbered `div` elements in the first `section`.
- `section:nth-of-type(1) div:nth-child(odd)`: Selects odd-numbered `div` elements in the first `section`.

### Example:
```css
section:first-of-type div {
    display: inline-block;
    width: 75px;
    height: 75px;
    border: 2px solid black;
}

section:nth-of-type(1) div:nth-child(even) {
    background-color: green;
}

section:nth-of-type(1) div:nth-child(odd) {
    background-color: yellow;
}
