# Breakpoint Mixin #

Breakpoint mixin makes it easy to create media queries.


### Installation ###

```
npm install --save iotacss-tools-breakpoint
```


#### Syntax ####

```sass
@include iota-breakpoint($breakpoint-size, $breakpoint-sizes)
```


#### Parameters ####

* $breakpoint-size: Size of the breakpoint you want to use
* $breakpoint-sizes: A Sass map that contains breakpoints. By default, uses $iota-global-breakpoints from [Settings.Core](https://github.com/iotacss/settings.core). This parameter is optional.


#### Example ####

```sass
.myClass {
  height: 100px;
  
  // Breakpoint for small screens
  @include iota-breakpoint(sm) {
    height: 150px;
  }
  
  // Breakpoint for medium screens
  @include iota-breakpoint(md, $my-breakpoints-sass-map) {
    height: 200px;
  }
}
```
