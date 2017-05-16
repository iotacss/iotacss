# Pull Utility #

The pull utility is responsible for handling grid's after offset.


### Installation ###

```
npm install --save iotacss-utils-pull
```


### Options ###

```sass
$iota-utils-pull-namespace    : 'pull-' !default;
$iota-utils-pull-delimiter    : $iota-global-delimiter !default;

$iota-utils-pull-columns      : $iota-global-columns !default;

$iota-utils-pull-res          : false !default;
$iota-utils-pull-breakpoints  : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-pull-[column-number]/[total-columns-number]  // Example: .u-pull-1/3


// Responsive Classes Syntax

.u-pull-[column-number]/[total-columns-number]@[breakpoint-name]  // Example: .u-pull-1/3@sm
```
