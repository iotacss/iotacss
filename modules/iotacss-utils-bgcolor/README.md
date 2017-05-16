# Background Color Utility #

The background color utility contains helper classes for the background-color CSS property.


### Installation ###

```
npm install --save iotacss-utils-bgcolor
```


### Options ###

```sass
$iota-utils-bgcolor-namespace : 'bgcolor-' !default;

$iota-utils-bgcolor-names     : () !default;
```


### Example ###

```sass
$iota-bgcolor-names: (
  white: #FFFFFF,
  black: #000000
);
```

It will generate:

```css
.u-bgcolor-white {
  background-color: #FFFFFF !important;
}

.u-bgcolor-black {
  background-color: #000000 !important;
}
```
