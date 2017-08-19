# border.css
[Opensource functional CSS border classes](#classes). Available [on npm](https://www.npmjs.com/package/border.css) for production and [unpkg](https://unpkg.com/border.css/) for [prototyping online](https://codepen.io/ryanve/pen/RZQqNX).

```
npm install border.css
```

### `@import` all

```css
@import 'node_modules/border.css/border';
```

### `@import` incrementally

```css
@import 'node_modules/border.css/border-collapse';
@import 'node_modules/border.css/border-color';
@import 'node_modules/border.css/border-style';
@import 'node_modules/border.css/border-width';
```

## [Classes](border.css)

### [`border-collapse`](border-collapse.css)
- `.border-separate`
- `.border-collapse`

### [`border-color`](border-color.css)
- `.border-current`
- `.border-transparent`

### [`border-style`](border-style.css)
- `.border-none`
  - `.top-none`
  - `.left-none`
  - `.right-none`
  - `.bottom-none`
- `.border-inset`
- `.border-groove`
- `.border-outset`
- `.border-ridge`
- `.border-dotted`
- `.border-dashed`
- `.border-solid`
- `.border-double`
- `.border-hidden`
  - `.top-hidden`
  - `.left-hidden`
  - `.right-hidden`
  - `.bottom-hidden`

### [`border-width`](border-width.css)
- `.border-zero`
  - `.top-zero`
  - `.left-zero`
  - `.right-zero`
  - `.bottom-zero`
- `.border-thin`
- `.border-medium`
- `.border-thick`
