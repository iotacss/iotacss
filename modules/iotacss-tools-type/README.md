# Type Tool

The type tool contains a mixin that helps you create smart, flexible and responsive typography.


### Installation

```
npm install --save iotacss-tools-type
```



## Mixins

```sass
@include iota-type($sizes, $breakpoints: $iota-global-breakpoints);
```

### Parameters

* sizes: number | list | map
* breakpoints: map of breakpoints, default is $iota-global-breakpoints




## Examples


### Simple Font Size

Use a number as a parameter to create simple font size.

```sass
$type-head-large: 26px;

.h1 {
  @include iota-type($type-head-large);
}
```

will generate:

```css
.h1 {
  font-size: 26px;
}
```


### Simple Font Size and Line Height

Use a list as a parameter to create simple font size and line-height.

```sass
$type-head-large: (26px, 30px);

.h1 {
  @include iota-type($type-head-large);
}
```

will generate:

```css
.h1 {
  font-size: 26px;
  line-leight: 30px;
}
```


### Responsive Font Size

Use a map as a parameter to create a responsive font-size.

```sass
$type-head-large: (
  null: 20px,
  sm: 26px
);

.h1 {
  @include iota-type($type-head-large);
}
```

will generate:

```css
.h1 {
  font-size: 20px;
}

@media screen and ( min-width: 768px ) {
  .h1 {
    font-size: 26px;
  }
}
```


### Responsive Font Size and Line Height

Use a map of lists as a parameter to create a responsive font-size and line-height.

```sass
$type-head-large: (
  null: (20px, 26px),
  sm: (26px, 30px)
);

.h1 {
  @include iota-type($type-head-large);
}
```

will generate:

```css
.h1 {
  font-size: 20px;
  line-height: 26px;
}

@media screen and ( min-width: 768px ) {
  .h1 {
    font-size: 26px;
    line-height: 30px;
  }
}
```


### Responsive Font Size and Line Height with Custom Breakpoints map

Use a map of lists as a first parameter to create a responsive font-size and line-height and a map of breakpoints as a second, to create responsive typography based on custom set of breakpoints.

```sass
$type-head-large: (
  null: (20px, 26px),
  smo: (26px, 30px)
);

$type-breakpoints: (
  smo: screen and ( min-width: 768px and max-width: 999px )
);

.h1 {
  @include iota-type($type-head-large, $type-breakpoints);
}
```

will generate:

```css
.h1 {
  font-size: 20px;
  line-height: 26px;
}

@media screen and ( min-width: 768px and max-width: 999px ) {
  .h1 {
    font-size: 26px;
    line-height: 30px;
  }
}
```

