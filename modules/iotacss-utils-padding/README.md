# Padding Utility #

The padding utility contains helper classes for the CSS padding property.


### Installation ###

```
npm install --save iotacss-utils-padding
```


### Options ###

```sass
$iota-utils-padding-namespace            : 'p' !default;
$iota-utils-padding-top-name             : 't' !default;
$iota-utils-padding-right-name           : 'r' !default;
$iota-utils-padding-bottom-name          : 'b' !default;
$iota-utils-padding-left-name            : 'l' !default;
$iota-utils-padding-vertical-name        : 'v' !default;
$iota-utils-padding-horizontal-name      : 'h' !default;

$iota-utils-padding-default              : $iota-global-gutter-default !default;
$iota-utils-padding-extra                : () !default;

$iota-utils-padding-res                  : false !default;
$iota-utils-padding-breakpoints          : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-p
.u-pt
.u-pr
.u-pb
.u-pl
.u-pv
.u-ph


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-p@sm
