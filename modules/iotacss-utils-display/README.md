# Display Utility #

The display utility contains helper classes for the CSS display property.


### Installation ###

```
npm install --save iotacss-utils-display
```


### Options ###

```sass
$iota-utils-display-namespace             : '' !default;
$iota-utils-display-block-name            : 'block' !default;
$iota-utils-display-hidden-name           : 'hidden' !default;
$iota-utils-display-inline-name           : 'inline' !default;
$iota-utils-display-inline-block-name     : 'inline-block' !default;

$iota-utils-display-res                   : false !default;
$iota-utils-display-breakpoints           : $iota-global-breakpoints !default;
```


### Classes ###

```css
.u-block
.u-hidden
.u-inline
.u-inline-block


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-block@sm
```
