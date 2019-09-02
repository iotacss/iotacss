# Fill Utility

The fill utility contains helper classes for the fill CSS property.

### Installation

```
npm install --save iotacss-utils-fill
```

### Options

```sass
$iota-utils-fill-namespace : 'fill-' !default;

$iota-utils-fill-names     : () !default;
```

### Example

```sass
$iota-fill-names: (
  white: #FFFFFF,
  black: #000000
);
```

It will generate:

```css
.u-fill-white {
    background-color: #ffffff !important;
}

.u-fill-black {
    background-color: #000000 !important;
}
```
