# Align Items Utility #

The alignitems utility contains helper classes for the CSS align-items property.


### Installation ###

```
npm install --save iotacss-utils-alignitems
```


### Options ###

```sass
$iota-utils-ai-namespace            : 'ai' !default;
$iota-utils-ai-start-name        	: 'flex-start' !default;
$iota-utils-ai-end-name           	: 'flex-end' !default;
$iota-utils-ai-center-name          : 'center' !default;
$iota-utils-ai-stretch-name         : 'stretch' !default;
$iota-utils-ai-baseline-name        : 'baseline' !default;

$iota-utils-ai-res                  : false !default;
$iota-utils-ai-breakpoints          : $iota-global-breakpoints !default;
```


### Classes ###

```css
.u-start
.u-end
.u-center
.u-stretch
.u-baseline


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: u-ai-start@sm
```
