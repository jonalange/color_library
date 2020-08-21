# color_library
A color library helper containing all the html ral panton values.
It is meant to be a helper object for color converters.

```javascript
const { html, pantone, ral } = require('color_library');

console.log(html) // and you get an array of all the posible html name colors

console.log(ral[0]) // { ral:1000, name:"GreenBeige", LRV:50, cmyk:{"c":0,"m":7,"y":32,"k":21}, rgb:{"r":201,"g":187,"b":136}, lab:{"l":76.022,"a":-0.366,"b":27.636}},

```

## structure 
*html*
{ name: "AliceBlue", rgb: { "r": 240, "g": 248, "b": 255 }},


*pantone*
{name:"100C", cmyk:{"c": 1 ,"m": 0 ,"y":"70","k":"0"}, rgb:{"r": 246,"g":235,"b":97}, lab:{"l":91.62764957506504,"a":-12.654196127772188,"b":66.37857444316361}},


*ral*
{ ral:1000, name:"GreenBeige", LRV:50, cmyk:{"c":0,"m":7,"y":32,"k":21}, rgb:{"r":201,"g":187,"b":136}, lab:{"l":76.022,"a":-0.366,"b":27.636}},


