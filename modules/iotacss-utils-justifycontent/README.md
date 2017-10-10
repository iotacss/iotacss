# Justify Content Utility #

The justify content utility contains helper classes for the CSS justify-content property.


### Installation ###

```
npm install --save iotacss-utils-justifycontent
```


### Options ###

```sass
$iota-utils-jc-namespace            : 'jc' !default;
$iota-utils-jc-start-name       	: 'start' !default;
$iota-utils-jc-end-name         	: 'end' !default;
$iota-utils-jc-center-name          : 'center' !default;
$iota-utils-jc-between-name    		: 'between' !default;
$iota-utils-jc-around-name     		: 'around' !default;

$iota-utils-jc-res                  : false !default;
$iota-utils-jc-breakpoints          : $iota-global-breakpoints !default;
```


### Classes ###

```css
.u-jc-start
.u-jc-end
.u-jc-center
.u-jc-between
.u-jc-around


// Responsive Class Syntax

.u-jc-[name]@[breakpoint-name]  // Example: u-jc-start@sm
```
