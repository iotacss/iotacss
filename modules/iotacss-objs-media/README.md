# Media Object #

The media object is an improved version of [@stubbornella's](https://twitter.com/stubbornella) media object.


### Installation ###

```
npm install --save iotacss-objs-media
```


### Options ###

```sass
$iota-objs-media-namespace            : 'media' !default;
$iota-objs-media-fixed-name           : 'fixed' !default;
$iota-objs-media-fluid-name           : 'fluid' !default;
$iota-objs-media-reversed-name        : 'rev' !default;
$iota-objs-media-align-middle-name    : 'middle' !default;
$iota-objs-media-align-bottom-name    : 'bottom' !default;
$iota-objs-media-responsive-name      : 'res' !default;

$iota-objs-media-gutter-default       : $iota-global-gutter-default !default;
$iota-objs-media-gutter-extra         : () !default;

$iota-objs-media-rev                  : false !default;

$iota-objs-media-aligned              : false !default;

$iota-objs-media-flex                 : $iota-global-flex !default;

$iota-objs-media-res                  : false !default;
$iota-objs-media-collapse-at          : 767px !default;
```


### Classes ###

```sass
.o-media
  .o-media__fixed
  .o-media__fluid


// Modifiers

.o-media--rev
.o-media--res
.o-media--middle
.o-media--bottom


// Extra gutter sizes

$iota-media-gutter-extra   : (
  small: 5px;
  large: 20px;
);

.o-list--small
.o-list--large
```
