# Flex Direction Utility #

The Flex Direction utility contains helper classes for the CSS flex-direction property.


### Installation ###

```
npm install --save iotacss-utils-flex-direction
```


### Options ###

```sass
$iota-utils-flex-direction-namespace              : 'fd-' !default;
$iota-utils-flex-direction-row-name               : 'row' !default;
$iota-utils-flex-direction-row-reverse-name       : 'rowrev' !default;
$iota-utils-flex-direction-column-name            : 'col' !default;
$iota-utils-flex-direction-column-reverse-name    : 'colrev' !default;

$iota-utils-flex-direction-res                    : false !default;
$iota-utils-flex-direction-breakpoints            : $iota-global-breakpoints !default;
```


### Classes ###

```css
.u-fd-row
.u-fd-rowrev
.u-fd-col
.u-fd-colrev


// Responsive Class Syntax

.u-fd-[name]@[breakpoint-name]  // Example: u-fd-row@sm
```
