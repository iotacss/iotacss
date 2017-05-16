# Opacity Utility #

The opacity utility contains helper classes for the opacity CSS property.


### Installation ###

```
npm install --save iotacss-utils-opacity
```


### Options ###

```sass
$iota-utils-opacity-namespace : 'opacity-' !default;

$iota-utils-opacity-sizes     : () !default;
```


### Example ###

```sass
$iota-utils-opacity-sizes: (
  30: 0.3,
  60: 0.6
);
```

It will generate:

```css
.u-opacity-30 {
  opacity: 0.3 !important;
}

.u-opacity-60 {
  opacity: 0.6 !important;
}
```
