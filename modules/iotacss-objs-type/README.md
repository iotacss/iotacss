# Type Object #

The type object is responsible for making responsive typography a piece of cake.


## Installation

```
npm install --save iotacss-objs-type
```


## Options

```sass
$iota-objs-type-namespace     : 'type-' !default;

$iota-objs-type-sizes         : () !default;
$iota-objs-type-breakpoints   : $iota-global-breakpoints !default;
```


## Examples


### Simple Font Size

Use a number as a value to create a simple font-size.

```sass
$iota-objs-type-sizes: (
  'head-large': 16px
);
```

It will generate:

```css
.o-type-head-large {
  font-size: 16px;
}
```


### Simple Font Size and Line Height

Use a list as a value to create a simple font-size and line-height.

```sass
$iota-objs-type-sizes: (
  'head-large': (16px, 20px)
);
```

It will generate:

```css
.o-type-head-large {
  font-size: 16px;
  line-height: 20px;
}
```


### Responsive Font Size

Use a map of numbers as a value to create a responsive font-size.

```sass
$iota-objs-type-sizes: (
  'head-large': (
    null: 16px,
    sm: 20px
  )
);
```

It will generate:

```css
.o-type-head-large {
  font-size: 16px;
}

@media screen and ( min-width: 768px ) {
  .o-type-head-large {
    font-size: 16px;
  }
}
```


### Responsive Font Size and Line Height

Use a map of lists as a value to create a responsive font-size and line-height.

```sass
$iota-objs-type-sizes: (
  'head-large': (
    null: (16px, 20px),
    sm: (20px, 26px)
  )
);
```

It will generate:

```css
.o-type-head-large {
  font-size: 16px;
  line-height: 20px;
}

@media screen and ( min-width: 768px ) {
  .o-type-head-large {
    font-size: 16px;
    line-height: 26px;
  }
}
```


### Responsive Font Size and Line Height with Custom Breakpoints

Use a set of custom breakpoints only for the type object. By default, it uses the default breakpoints.

```sass
$iota-objs-type-sizes: (
  'head-large': (
    null: (16px, 20px),
    smo: (20px, 26px)
  )
);

$iota-objs-type-breakpoints: (
  smo: "screen and ( min-width: 768px and max-width: 999px )"
);
```

It will generate:

```css
.o-type-head-large {
  font-size: 16px;
  line-height: 20px;
}

@media screen and ( min-width: 768px and max-width: 999px ) {
  .o-type-head-large {
    font-size: 16px;
    line-height: 26px;
  }
}
```
