# Shadow Tool

The shadow tool needs to be plugged in between the settings and iotaCSS itself. It's goal is to reduce the globally defined maps in your settings to a selected set of actually used values and then import utils, tools and objects as they are used in your component.

This is important to keep ShadowDOM encapsulated web components' CSS at an acceptable size, because each individual web component needs to receive all resets and styling values it needs. So the alternatives would be, to write your css per component or to include your complete css code in every web component you use. The Shadow Tool tries make it possible for developers to rely on a solid framework with global settings which enables a consistent global style, extended by custom css code where needed, while keeping the CSS styles at a reasonable size.


### Installation

```
npm install --save iotacss-tools-shadow
```
