# Float Utility #

The float utility contains helper classes for the CSS float property.


### Installation ###

```
npm install --save iotacss-utils-float
```


### Options ###

```sass
$iota-utils-float-namespace             : 'float-' !default;
$iota-utils-float-left-name             : 'left' !default;
$iota-utils-float-right-name            : 'right' !default;

$iota-utils-float-res                   : false !default;
$iota-utils-float-breakpoints           : $iota-global-breakpoints !default;
```


### Classes ###

```css
.u-float-left
.u-float-right


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-float-left@sm
```
