# Justify Content Utility #

The justify content utility contains helper classes for the CSS justify-content property.


### Installation ###

```
npm install --save iotacss-utils-justifycontent
```


### Options ###

```sass
$iota-utils-justify-content-namespace           : 'jc' !default;
$iota-utils-justify-content-start-name       	: 'start' !default;
$iota-utils-justify-content-end-name         	: 'end' !default;
$iota-utils-justify-content-center-name         : 'center' !default;
$iota-utils-justify-content-between-name    	: 'between' !default;
$iota-utils-justify-content-around-name     	: 'around' !default;

$iota-utils-justify-content-res                 : false !default;
$iota-utils-justify-content-breakpoints         : $iota-global-breakpoints !default;
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
