# Push Utility #

The push utility is responsible for handling grid's before offset.


### Installation ###

```
npm install --save iotacss-utils-push
```


### Options ###

```sass
$iota-utils-push-namespace    : 'push-' !default;
$iota-utils-push-delimiter    : $iota-global-delimiter !default;

$iota-utils-push-columns      : $iota-global-columns !default;

$iota-utils-push-res          : false !default;
$iota-utils-push-breakpoints  : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-push-[column-number]/[total-columns-number]  // Example: .u-push-1/3


// Responsive Classes Syntax

.u-push-[column-number]/[total-columns-number]@[breakpoint-name]  // Example: .u-push-1/3@sm
```
