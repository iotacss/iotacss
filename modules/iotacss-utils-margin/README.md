# Margin Utility #

The margin utility contains helper classes for the CSS margin property.


### Installation ###

```
npm install --save iotacss-utils-margin
```


### Options ###

```sass
$iota-utils-margin-namespace            : 'm' !default;
$iota-utils-margin-top-name             : 't' !default;
$iota-utils-margin-right-name           : 'r' !default;
$iota-utils-margin-bottom-name          : 'b' !default;
$iota-utils-margin-left-name            : 'l' !default;
$iota-utils-margin-vertical-name        : 'v' !default;
$iota-utils-margin-horizontal-name      : 'h' !default;

$iota-utils-margin-default              : $iota-global-gutter-default !default;
$iota-utils-margin-extra                : () !default;

$iota-utils-margin-res                  : false !default;
$iota-utils-margin-breakpoints          : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-m
.u-mt
.u-mr
.u-mb
.u-ml
.u-mv
.u-mh


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-m@sm
