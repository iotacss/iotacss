# Align Utility #

The align utility contains helper classes for the CSS vertical align property.


### Installation ###

```
npm install --save iotacss-utils-align
```


### Options ###

```sass
$iota-utils-align-namespace     : 'align-' !default;
$iota-utils-align-top-name      : 'top' !default;
$iota-utils-align-bottom-name   : 'bottom' !default;
$iota-utils-align-middle-name   : 'middle' !default;
$iota-utils-align-baseline-name : 'baseline' !default;

$iota-utils-align-res           : false !default;
$iota-utils-align-breakpoints   : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-align-top
.u-align-bottom
.u-align-middle
.u-align-baseline


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-align-top@sm
```
