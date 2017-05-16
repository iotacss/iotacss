# Grid Object #

The grid object is responsible for building a smart grid when used with [Size](https://github.com/iotacss/utilities.size), [Push](https://github.com/iotacss/utilities.push) or [Pull](https://github.com/iotacss/utilities.push) utilities.


### Installation ###

```
npm install --save iotacss-objs-grid
```


### Options ###

```sass
$iota-objs-grid-namespace          : 'grid' !default;
$iota-objs-grid-column-name        : 'col' !default;
$iota-objs-grid-align-right-name   : 'right' !default;
$iota-objs-grid-align-center-name  : 'center' !default;
$iota-objs-grid-align-top-name     : 'top' !default;
$iota-objs-grid-align-middle-name  : 'middle' !default;
$iota-objs-grid-align-bottom-name  : 'bottom' !default;
$iota-objs-grid-align-around-name  : 'around' !default;
$iota-objs-grid-align-between-name : 'between' !default;
$iota-objs-grid-reverse-name       : 'rev' !default;
$iota-objs-grid-equal-height-name  : 'equal-height' !default;

$iota-objs-grid-gutter-default     : $iota-global-gutter-default !default;
$iota-objs-grid-gutter-extra       : () !default;

$iota-objs-grid-aligned            : false !default;

$iota-objs-grid-rev                : false !default;

$iota-objs-grid-flex               : $iota-global-flex !default;
$iota-objs-grid-equal-height       : false !default;
```


### Example

```html
<div class="o-grid">

    <div class="o-grid__col u-1/2">
      Column 1
    </div><!--

 --><div class="o-grid__col u-1/2">
      Column 2
    </div>

</div>
```

Do you see this empty HTML comment '<!-- -->'? This is used to fight the space between the grid columns, because they are inline block elements. If you want to read more about this fix or find some alternatives, head over [here](https://css-tricks.com/fighting-the-space-between-inline-block-elements/).
