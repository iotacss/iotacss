# Justify Content Utility #

The justify content utility contains helper classes for the CSS justify-content property.


### Installation ###

```
npm install --save iotacss-utils-justifycontent
```


### Options ###

```sass
$iota-utils-justifycontent-namespace            : '' !default;
$iota-utils-justifycontent-flexstart-name       : 'flexstart' !default;
$iota-utils-justifycontent-flexend-name         : 'flexend' !default;
$iota-utils-justifycontent-center-name          : 'center' !default;
$iota-utils-justifycontent-spacebetween-name    : 'spacebetween' !default;
$iota-utils-justifycontent-spacearound-name     : 'spacearound' !default;

$iota-utils-justifycontent-res                  : false !default;
$iota-utils-justifycontent-breakpoints          : $iota-global-breakpoints !default;
```


### Classes ###

```css
.u-jc-flexstart
.u-jc-flexend
.u-jc-center
.u-jc-spacebetween
.u-jc-spacearound


// Responsive Class Syntax

.u-jc-[name]@[breakpoint-name]  // Example: u-jc-flexstart@sm
```
