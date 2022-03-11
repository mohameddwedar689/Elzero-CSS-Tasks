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

