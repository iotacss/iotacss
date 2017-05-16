# Weight Utility #

The weight utility contains helper classes for the font-weight CSS property.


### Installation ###

```
npm install --save iotacss-utils-weight
```


### Options ###

```
$iota-utils-weight-namespace  : 'weight-' !default;

$iota-utils-weight-sizes      : () !default;
```


### Example ###

```sass
$iota-utils-weight-sizes: (
  thin    : 300,
  normal  : 400,
  bold    : 700
);
```

It will generate:

```css
.u-weight-thin {
  font-weight: 300 !important;
}

.u-weight-normal {
  font-weight: 400 !important;
}

.u-weight-bold {
  font-weight: 700 !important;
}
```
