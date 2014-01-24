# geojson-tools

# This is a wish list for a geojson npm package. There is no code backing this (yet).

# Installation
````
npm install geojson-tools --save
````

# Examples
````javascript
var tools = require('geojson-tools');

tools.validate(geojson);

tools.merge(geojson1, geojson2);

tools.simplify(geojson, tolerance);

tools.rewind(polygon);

tools.area(polygon);

tools.flatten(polygon1, polygon2, ...);



````
