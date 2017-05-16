# Core Settings

The core settings file contains all the important settings for iotaCSS to work.


### Installation

```
npm install --save iotacss-settings-core
```


### Options

```sass
// Defines that iota core settings has been loaded

$iota-settings-core: true;




// Defines the default iota columns

$iota-global-columns: 2, 3, 6 !default;




// Defines the iota default namespaces

$iota-global-objects-namespace    : 'o-' !default;
$iota-global-utilities-namespace  : 'u-' !default;
$iota-global-components-namespace : 'c-' !default;




// Defines the default spacing size

$iota-global-gutter-default: 10px !default;




// Enables flexbox across the app

$iota-global-flex: false !default;




// Enables rtl across the app

$iota-global-rtl: false !default;




// Defines iotaCSS default breakpoints

$iota-global-breakpoints: (
  sm  : "screen and ( min-width: 768px )",
  smo : "screen and (min-width: 768px ) and (max-width: 999px )",
  md  : "screen and ( min-width: 1000px )"
) !default;




// Defines the default breakpoint separator

$iota-global-breakpoint-separator: \@ !default;




// Defines the default delimiter for Size, Push and Pull utilities

$iota-global-delimiter: \/ !default;
```
