# List Object #

The list object is responsible for creating inline, block and span lists.


### Installation ###

```
npm install --save iotacss-objs-list
```


### Options ###

```sass
$iota-objs-list-namespace         : 'list' !default;
$iota-objs-list-item-name         : 'item' !default;
$iota-objs-list-block-name        : 'block' !default;
$iota-objs-list-inline-name       : 'inline' !default;
$iota-objs-list-span-name         : 'span' !default;
$iota-objs-list-align-middle-name : 'middle' !default;
$iota-objs-list-align-bottom-name : 'bottom' !default;

$iota-objs-list-gutter-default    : $iota-global-gutter-default !default;
$iota-objs-list-gutter-extra      : () !default;

$iota-objs-list-block             : false !default;
$iota-objs-list-inline            : false !default;
$iota-objs-list-span              : false !default;

$iota-objs-list-aligned           : false !default;
```


### Classes ###

```sass
.o-list
  .o-list__item


// Modifiers

.o-list--block
.o-list--inline
.o-list--span
.o-list--middle
.o-list--bottom


// Extra gutter sizes

$iota-list-gutter-extra   : (
  small: 5px;
  large: 20px;
);

.o-list--small
.o-list--large
```
