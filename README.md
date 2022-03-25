# **Important Notes In CSS Assignment👋**

---

## Week 1️⃣

### CSS Color

Colors in CSS can be specified by the following methods:

- Hexadecimal colors
- Hexadecimal colors with transparency
- RGB colors
- RGBA colors
- HSL colors
- HSLA colors
- Predefined/Cross-browser color names
- With the `currentcolor` keyword

### CSS Background Properties

The `background` property is a shorthand property for:

- background-color
- background-image
- background-position
- background-size
- background-repeat
- background-origin
- background-clip
- background-attachment

### CSS Display

The `display` property specifies the display behavior (the type of rendering box) of an element.

## Week 2️⃣

### CSS Font

In CSS, we use the `font-family` property to specify the font of a text.

The `font-style` property is mostly used to specify (normal text - italic text  - oblique text).

The `font-size` property sets the size of the text.

To shorten the code, it is also possible to specify all the individual font properties in one property you can use `font`

The `font` property is a shorthand property for:

- `font-style`
- `font-variant`
- `font-weight`
- `font-size/line-height`
- `font-family`

### CSS Units

CSS has several different units for expressing a length.

Many CSS properties take "length" values, such as `width`, `margin`, `padding`, `font-size`, etc.

**Length** is a number followed by a length unit, such as `10px`, `2em`, etc.

**Absolute Length**

| Unit |       **Description**        |
| :--: | :--------------------------: |
|  cm  |         centimeters          |
|  mm  |         millimeters          |
|  in  | inches (1in = 96px = 2.54cm) |
|  px  | pixels (1px = 1/96th of 1in) |
|  pt  |  points (1pt = 1/72 of 1in)  |
|  pc  |     picas (1pc = 12 pt)      |

**Relative Length**

| Unit |                         Description                          |
| :--: | :----------------------------------------------------------: |
|  em  | Relative to the font-size of the element (2em means 2 times the size of the current font) |
|  ex  |  Relative to the x-height of the current font (rarely used)  |
|  ch  |           Relative to the width of the "0" (zero)            |
| rem  |          Relative to font-size of the root element           |
|  vw  |         Relative to 1% of the width of the viewport*         |
|  vh  |        Relative to 1% of the height of the viewport*         |
| vmin |       Relative to 1% of viewport's* smaller dimension        |
| vmax |        Relative to 1% of viewport's* larger dimension        |
|  %   |                Relative to the parent element                |

## Week 3️⃣

### CSS Position

The `position` property specifies the type of positioning method used for an element.

There are five different position values:

- `static`
- `relative`
- `fixed`
- `absolute`
- `sticky`

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the `position` property is set first. They also work differently depending on the position value.

## Week 4️⃣

### CSS Box Model

All HTML elements can be considered as boxes.

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

![box_model](https://user-images.githubusercontent.com/77099631/157864551-0f4c4c78-5c33-4de4-8fd4-d3d1082d7176.png)

Explanation of the different parts:

- **Content** - The content of the box, where text and images appear
- **Padding** - Clears an area around the content. The padding is transparent
- **Border** - A border that goes around the padding and content
- **Margin** - Clears an area outside the border. The margin is transparent

## Week 5️⃣

### CSS Flex

**Flexbox** is a one-dimensional layout method for arranging items in rows or columns. Items *flex* (expand) to fill additional space or shrink to fit into smaller spaces. This article explains all the fundamentals.

To start with, we need to select which elements are to be laid out as flexible boxes. To do this, we set a special value of `display` 

on the parent element of the elements you want to affect. In this case we want to lay out the element 

```CSS
.section {
    display: flex;
}
```

### The flex model

<img src="https://user-images.githubusercontent.com/77099631/159008692-11b1f043-ac5e-4f96-8db9-c1cc4b830e7a.png" alt="flex_terms" style="zoom:150%;" />

## Week 6️⃣

### CSS Filters

The **`filter`** CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

### CSS Grid

The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

An HTML element becomes a grid container when its `display` property is set to `grid` or `inline-grid`.

```CSS
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto;
}
.item {
  grid-column: 1 / 5;
}
```

## Week 7️⃣

### CSS Angle Tan

The **`<angle>`**CSS data type represents an angle value expressed in degrees, gradians, radians, or turns. It is used, for example, in sand in some `transform` functions.

### CSS Transform

The `transform` property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.

## Week 8️⃣

### CSS Media Queries Breakpoints

- **Breakpoints based on device**

```css
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {...}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {...}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {...}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {...}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {...}
```

### CSS Selectors

In CSS, selectors are patterns used to select the element(s) you want to style.
