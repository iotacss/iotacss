# Modular Scale Tool

The Modular Scale tool contains a function that helps you create sizes based on modular scale.


### Installation

```
npm install --save iotacss-tools-ms
```


### Options

```scss
$iota-tools-ms-base   : 15px !default;
$iota-tools-ms-ratio  : 1.2 !default;
$iota-tools-ms-scale  : 3 !default;
```

**Since v1.1.0, all variables have '$iota-tools-ms' instead of '$iota-ms' prefix and the '$iota-ms-digits' renamed to '$iota-tools-ms-scale'.**


### Function Syntax

```sass
@include iota-ms($increment,
  $base   : $iota-tools-ms-base,
  $ratio  : $iota-tools-ms-ratio,
  $scale  : $iota-tools-ms-scale
);
```


### Parameters

* increment: unitless number - Number of steps to increment up or down the scale
* base: number - The base value the scale starts at. Defaults to  $iota-ms-base;
* ratio: unitless number - The ratio the scale is built on. Defaults to $iota-ms-ratio.
* scale: unitless number - Length of scale ( right part of the decimal point ) ms will be rounded to. Defaults to $iota-tools-ms-scale.


## Examples


### Modular scale with 16px base, 1.5 ratio rounded to 2 digits

You can either adjust the default options:

```sass
$iota-tools-ms-base   : 16px;
$iota-tools-ms-ratio  : 1.5;
$iota-tools-ms-scale  : 2;

.h1 {
  font-size: iota-ms(2); // 36px
}
```

or you can just pass the options directly to the function:

```css
.h1 {
  font-size: iota-ms(2, 16px, 1.5, 2); // 36px
}
```
