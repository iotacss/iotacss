# Box Shadow Utility

The box shadow utility contains helper classes for the box-shadow CSS property.

### Installation

```
npm install --save iotacss-utils-shadow
```

### Options

```sass
$iota-utils-shadow-namespace : 'shadow-' !default;

$iota-utils-shadow-names     : () !default;
```

### Example

```sass
$iota-shadow-names: (
    1: 0px 2px 10px rgba(0, 0, 0, 0.1),
    2: 0px 4px 20px rgba(0, 0, 0, 0.2)
);
```

It will generate:

```css
.u-shadow-1 {
    box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1) !important;
}

.u-shadow-2 {
    box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.2) !important;
}
```
