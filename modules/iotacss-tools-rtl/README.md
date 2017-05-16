# RTL Tool

The tools rtl file contains all the important mixins and functions for developing an right-to-left website.


### Installation

```
npm install --save iotacss-tools-rtl
```


## Mixins


### Align Content

```sass
@include align-content(flex-start / flex-end);
```


### Align Self

```sass
@include align-self(flex-start / flex-end);
```


### Border

```sass
@include iota-border-left($value);
@include iota-border-right($value);
```


### Border Color

```sass
@include iota-border-left-color($value);
@include iota-border-right-color($value);
@include iota-border-color($list);
```


### Border Radius

```sass
@include iota-border-top-radius($value);
@include iota-border-right-radius($value);
@include iota-border-bottom-radius($value);
@include iota-border-left-radius($value);
@include iota-border-top-left-radius($value);
@include iota-border-top-right-radius($value);
@include iota-border-bottom-left-radius($value);
@include iota-border-bottom-right-radius($value);
```


### Border Style

```sass
@include iota-border-left-style($value);
@include iota-border-right-style($value);
@include iota-border-style($list);
```


### Border Width

```sass
@include iota-border-left-width($value);
@include iota-border-right-width($value);
@include iota-border-width($list);
```


### Clear

```sass
@include iota-align-self(left / right);
```


### Direction

```sass
@include iota-direction(ltr / rtl);
```


### Justify Content

```sass
@include iota-justify-content(flex-start / flex-end);
```


### Left / Right

```sass
@include iota-left($value);
@include iota-right($value);
```


### Margin

```sass
@include iota-margin-left($value);
@include iota-margin-right($value);
@include iota-margin($list);
```


### Padding

```sass
@include iota-padding-left($value);
@include iota-padding-right($value);
@include iota-padding($list);
```


### Text Align

```sass
@include iota-text-align(left / right);
```
